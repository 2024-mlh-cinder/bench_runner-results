
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.06x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| chameleon      | 7.42 ms                                                      | 7.22 ms: 1.03x faster                                      |
| tornado_http   | 125 ms                                                       | 121 ms: 1.03x faster                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                               |

Benchmark hidden because not significant (2): 2to3, docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_memoization     | 648 ms                                                       | 554 ms: 1.17x faster                                       |
| async_tree_none            | 529 ms                                                       | 461 ms: 1.15x faster                                       |
| async_tree_io              | 1.19 sec                                                     | 1.06 sec: 1.12x faster                                     |
| async_tree_memoization_tg  | 605 ms                                                       | 551 ms: 1.10x faster                                       |
| async_tree_none_tg         | 482 ms                                                       | 439 ms: 1.10x faster                                       |
| async_tree_io_tg           | 1.17 sec                                                     | 1.07 sec: 1.10x faster                                     |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 706 ms: 1.08x faster                                       |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 706 ms: 1.08x faster                                       |
| Geometric mean             | (ref)                                                        | 1.11x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 86.1 ms: 1.11x faster                                      |
| float          | 76.0 ms                                                      | 78.9 ms: 1.04x slower                                      |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 143 ms: 1.10x faster                                       |
| regex_effbot   | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                      |
| regex_v8       | 23.7 ms                                                      | 24.4 ms: 1.03x slower                                      |
| regex_dna      | 226 ms                                                       | 247 ms: 1.09x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                      |
| json_loads           | 29.0 us                                                      | 24.2 us: 1.20x faster                                      |
| unpickle_pure_python | 236 us                                                       | 211 us: 1.12x faster                                       |
| xml_etree_parse      | 159 ms                                                       | 149 ms: 1.06x faster                                       |
| tomli_loads          | 2.27 sec                                                     | 2.19 sec: 1.04x faster                                     |
| xml_etree_iterparse  | 106 ms                                                       | 103 ms: 1.03x faster                                       |
| pickle_pure_python   | 318 us                                                       | 321 us: 1.01x slower                                       |
| pickle_dict          | 31.8 us                                                      | 32.4 us: 1.02x slower                                      |
| xml_etree_process    | 56.1 ms                                                      | 58.6 ms: 1.04x slower                                      |
| pickle               | 9.77 us                                                      | 10.2 us: 1.04x slower                                      |
| xml_etree_generate   | 80.5 ms                                                      | 85.8 ms: 1.07x slower                                      |
| unpickle_list        | 4.47 us                                                      | 4.78 us: 1.07x slower                                      |
| unpickle             | 13.2 us                                                      | 14.6 us: 1.11x slower                                      |
| pickle_list          | 3.89 us                                                      | 4.50 us: 1.16x slower                                      |
| Geometric mean       | (ref)                                                        | 1.02x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.08x slower                                      |
| python_startup_no_site | 7.78 ms                                                      | 8.66 ms: 1.11x slower                                      |
| Geometric mean         | (ref)                                                        | 1.10x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 11.0 ms                                                      | 10.0 ms: 1.10x faster                                      |
| django_template | 40.4 ms                                                      | 39.3 ms: 1.03x faster                                      |
| Geometric mean  | (ref)                                                        | 1.06x faster                                               |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf2-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 154 us: 3.41x faster                                       |
| asyncio_tcp                | 752 ms                                                       | 381 ms: 1.97x faster                                       |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.57 sec: 1.96x faster                                     |
| generators                 | 56.4 ms                                                      | 36.7 ms: 1.53x faster                                      |
| json_dumps                 | 13.5 ms                                                      | 10.2 ms: 1.32x faster                                      |
| fannkuch                   | 457 ms                                                       | 353 ms: 1.30x faster                                       |
| richards_super             | 65.2 ms                                                      | 51.1 ms: 1.28x faster                                      |
| deltablue                  | 4.03 ms                                                      | 3.30 ms: 1.22x faster                                      |
| coroutines                 | 27.9 ms                                                      | 23.0 ms: 1.21x faster                                      |
| json_loads                 | 29.0 us                                                      | 24.2 us: 1.20x faster                                      |
| hexiom                     | 6.97 ms                                                      | 5.95 ms: 1.17x faster                                      |
| async_tree_memoization     | 648 ms                                                       | 554 ms: 1.17x faster                                       |
| async_tree_none            | 529 ms                                                       | 461 ms: 1.15x faster                                       |
| scimark_lu                 | 115 ms                                                       | 101 ms: 1.14x faster                                       |
| comprehensions             | 24.8 us                                                      | 21.8 us: 1.14x faster                                      |
| sympy_sum                  | 184 ms                                                       | 162 ms: 1.13x faster                                       |
| sympy_expand               | 550 ms                                                       | 490 ms: 1.12x faster                                       |
| async_tree_io              | 1.19 sec                                                     | 1.06 sec: 1.12x faster                                     |
| unpickle_pure_python       | 236 us                                                       | 211 us: 1.12x faster                                       |
| richards                   | 49.9 ms                                                      | 44.7 ms: 1.11x faster                                      |
| chaos                      | 71.6 ms                                                      | 64.3 ms: 1.11x faster                                      |
| nbody                      | 95.8 ms                                                      | 86.1 ms: 1.11x faster                                      |
| go                         | 166 ms                                                       | 149 ms: 1.11x faster                                       |
| sqlglot_parse              | 1.55 ms                                                      | 1.40 ms: 1.11x faster                                      |
| sympy_str                  | 336 ms                                                       | 304 ms: 1.10x faster                                       |
| gc_traversal               | 4.06 ms                                                      | 3.69 ms: 1.10x faster                                      |
| regex_compile              | 157 ms                                                       | 143 ms: 1.10x faster                                       |
| async_tree_memoization_tg  | 605 ms                                                       | 551 ms: 1.10x faster                                       |
| async_tree_none_tg         | 482 ms                                                       | 439 ms: 1.10x faster                                       |
| mako                       | 11.0 ms                                                      | 10.0 ms: 1.10x faster                                      |
| async_tree_io_tg           | 1.17 sec                                                     | 1.07 sec: 1.10x faster                                     |
| json                       | 5.59 ms                                                      | 5.12 ms: 1.09x faster                                      |
| logging_silent             | 102 ns                                                       | 93.7 ns: 1.09x faster                                      |
| nqueens                    | 99.2 ms                                                      | 91.3 ms: 1.09x faster                                      |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 706 ms: 1.08x faster                                       |
| sqlglot_transpile          | 1.94 ms                                                      | 1.80 ms: 1.08x faster                                      |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 706 ms: 1.08x faster                                       |
| sqlalchemy_imperative      | 19.9 ms                                                      | 18.6 ms: 1.07x faster                                      |
| sympy_integrate            | 25.6 ms                                                      | 24.0 ms: 1.07x faster                                      |
| xml_etree_parse            | 159 ms                                                       | 149 ms: 1.06x faster                                       |
| dask                       | 417 ms                                                       | 393 ms: 1.06x faster                                       |
| mdp                        | 2.72 sec                                                     | 2.57 sec: 1.06x faster                                     |
| bench_thread_pool          | 1.02 ms                                                      | 963 us: 1.06x faster                                       |
| logging_simple             | 7.21 us                                                      | 6.86 us: 1.05x faster                                      |
| logging_format             | 7.83 us                                                      | 7.51 us: 1.04x faster                                      |
| deepcopy                   | 389 us                                                       | 374 us: 1.04x faster                                       |
| dulwich_log                | 68.3 ms                                                      | 65.6 ms: 1.04x faster                                      |
| tomli_loads                | 2.27 sec                                                     | 2.19 sec: 1.04x faster                                     |
| coverage                   | 66.6 ms                                                      | 64.2 ms: 1.04x faster                                      |
| tornado_http               | 125 ms                                                       | 121 ms: 1.03x faster                                       |
| pycparser                  | 1.28 sec                                                     | 1.24 sec: 1.03x faster                                     |
| xml_etree_iterparse        | 106 ms                                                       | 103 ms: 1.03x faster                                       |
| django_template            | 40.4 ms                                                      | 39.3 ms: 1.03x faster                                      |
| chameleon                  | 7.42 ms                                                      | 7.22 ms: 1.03x faster                                      |
| spectral_norm              | 94.0 ms                                                      | 91.5 ms: 1.03x faster                                      |
| pyflate                    | 453 ms                                                       | 441 ms: 1.03x faster                                       |
| scimark_monte_carlo        | 70.6 ms                                                      | 68.8 ms: 1.03x faster                                      |
| scimark_sor                | 109 ms                                                       | 108 ms: 1.01x faster                                       |
| raytrace                   | 308 ms                                                       | 304 ms: 1.01x faster                                       |
| deepcopy_memo              | 37.3 us                                                      | 36.8 us: 1.01x faster                                      |
| sqlglot_normalize          | 122 ms                                                       | 121 ms: 1.01x faster                                       |
| crypto_pyaes               | 81.8 ms                                                      | 80.9 ms: 1.01x faster                                      |
| meteor_contest             | 130 ms                                                       | 131 ms: 1.01x slower                                       |
| sqlglot_optimize           | 59.2 ms                                                      | 59.6 ms: 1.01x slower                                      |
| pickle_pure_python         | 318 us                                                       | 321 us: 1.01x slower                                       |
| gunicorn                   | 986 us                                                       | 1.00 ms: 1.02x slower                                      |
| pickle_dict                | 31.8 us                                                      | 32.4 us: 1.02x slower                                      |
| regex_effbot               | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                      |
| regex_v8                   | 23.7 ms                                                      | 24.4 ms: 1.03x slower                                      |
| deepcopy_reduce            | 3.37 us                                                      | 3.48 us: 1.03x slower                                      |
| pprint_safe_repr           | 780 ms                                                       | 805 ms: 1.03x slower                                       |
| sqlalchemy_declarative     | 155 ms                                                       | 160 ms: 1.03x slower                                       |
| float                      | 76.0 ms                                                      | 78.9 ms: 1.04x slower                                      |
| aiohttp                    | 984 us                                                       | 1.02 ms: 1.04x slower                                      |
| xml_etree_process          | 56.1 ms                                                      | 58.6 ms: 1.04x slower                                      |
| pickle                     | 9.77 us                                                      | 10.2 us: 1.04x slower                                      |
| scimark_fft                | 281 ms                                                       | 295 ms: 1.05x slower                                       |
| pidigits                   | 251 ms                                                       | 265 ms: 1.05x slower                                       |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.26 ms: 1.06x slower                                      |
| xml_etree_generate         | 80.5 ms                                                      | 85.8 ms: 1.07x slower                                      |
| telco                      | 6.91 ms                                                      | 7.39 ms: 1.07x slower                                      |
| unpickle_list              | 4.47 us                                                      | 4.78 us: 1.07x slower                                      |
| python_startup             | 10.8 ms                                                      | 11.7 ms: 1.08x slower                                      |
| regex_dna                  | 226 ms                                                       | 247 ms: 1.09x slower                                       |
| sqlite_synth               | 2.49 us                                                      | 2.72 us: 1.09x slower                                      |
| unpickle                   | 13.2 us                                                      | 14.6 us: 1.11x slower                                      |
| python_startup_no_site     | 7.78 ms                                                      | 8.66 ms: 1.11x slower                                      |
| pickle_list                | 3.89 us                                                      | 4.50 us: 1.16x slower                                      |
| async_generators           | 322 ms                                                       | 391 ms: 1.22x slower                                       |
| unpack_sequence            | 44.9 ns                                                      | 57.2 ns: 1.27x slower                                      |
| bench_mp_pool              | 4.63 ms                                                      | 6.23 ms: 1.35x slower                                      |
| Geometric mean             | (ref)                                                        | 1.06x faster                                               |

Benchmark hidden because not significant (7): create_gc_cycles, asyncio_websockets, docutils, 2to3, pathlib, pprint_pformat, mypy2
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
