
# Results vs. 3.12.0

- fork: python
- ref: v3.11.0
- machine: linux-x86_64
- commit hash: deaf509
- commit date: 2022-10-24
- overall geometric mean: 1.07x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 285 ms                                                       | 286 ms: 1.00x slower                                         |
| chameleon      | 7.27 ms                                                      | 7.42 ms: 1.02x slower                                        |
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                       |
| tornado_http   | 122 ms                                                       | 125 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x slower                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 760 ms: 1.08x slower                                         |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 762 ms: 1.08x slower                                         |
| async_tree_memoization_tg  | 554 ms                                                       | 605 ms: 1.09x slower                                         |
| async_tree_io_tg           | 1.07 sec                                                     | 1.17 sec: 1.09x slower                                       |
| async_tree_none_tg         | 440 ms                                                       | 482 ms: 1.10x slower                                         |
| async_tree_io              | 1.06 sec                                                     | 1.19 sec: 1.13x slower                                       |
| async_tree_none            | 459 ms                                                       | 529 ms: 1.15x slower                                         |
| async_tree_memoization     | 554 ms                                                       | 648 ms: 1.17x slower                                         |
| Geometric mean             | (ref)                                                        | 1.11x slower                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 81.6 ms                                                      | 76.0 ms: 1.07x faster                                        |
| pidigits       | 264 ms                                                       | 251 ms: 1.05x faster                                         |
| nbody          | 88.2 ms                                                      | 95.8 ms: 1.09x slower                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_dna      | 240 ms                                                       | 226 ms: 1.06x faster                                         |
| regex_effbot   | 3.61 ms                                                      | 3.42 ms: 1.06x faster                                        |
| regex_v8       | 24.4 ms                                                      | 23.7 ms: 1.03x faster                                        |
| regex_compile  | 145 ms                                                       | 157 ms: 1.09x slower                                         |
| Geometric mean | (ref)                                                        | 1.02x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle             | 15.3 us                                                      | 13.2 us: 1.16x faster                                        |
| pickle_list          | 4.22 us                                                      | 3.89 us: 1.08x faster                                        |
| xml_etree_generate   | 85.3 ms                                                      | 80.5 ms: 1.06x faster                                        |
| unpickle_list        | 4.65 us                                                      | 4.47 us: 1.04x faster                                        |
| xml_etree_process    | 58.3 ms                                                      | 56.1 ms: 1.04x faster                                        |
| pickle               | 10.0 us                                                      | 9.77 us: 1.03x faster                                        |
| pickle_dict          | 32.0 us                                                      | 31.8 us: 1.01x faster                                        |
| pickle_pure_python   | 319 us                                                       | 318 us: 1.00x faster                                         |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                         |
| tomli_loads          | 2.17 sec                                                     | 2.27 sec: 1.05x slower                                       |
| xml_etree_parse      | 147 ms                                                       | 159 ms: 1.08x slower                                         |
| unpickle_pure_python | 210 us                                                       | 236 us: 1.13x slower                                         |
| json_loads           | 24.3 us                                                      | 29.0 us: 1.19x slower                                        |
| json_dumps           | 10.3 ms                                                      | 13.5 ms: 1.31x slower                                        |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup_no_site | 8.67 ms                                                      | 7.78 ms: 1.11x faster                                        |
| python_startup         | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                        |
| Geometric mean         | (ref)                                                        | 1.10x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| django_template | 38.7 ms                                                      | 40.4 ms: 1.04x slower                                        |
| mako            | 10.1 ms                                                      | 11.0 ms: 1.09x slower                                        |
| Geometric mean  | (ref)                                                        | 1.07x slower                                                 |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpack_sequence            | 54.5 ns                                                      | 44.9 ns: 1.21x faster                                        |
| async_generators           | 385 ms                                                       | 322 ms: 1.20x faster                                         |
| unpickle                   | 15.3 us                                                      | 13.2 us: 1.16x faster                                        |
| python_startup_no_site     | 8.67 ms                                                      | 7.78 ms: 1.11x faster                                        |
| scimark_sparse_mat_mult    | 4.49 ms                                                      | 4.04 ms: 1.11x faster                                        |
| sqlite_synth               | 2.72 us                                                      | 2.49 us: 1.09x faster                                        |
| pickle_list                | 4.22 us                                                      | 3.89 us: 1.08x faster                                        |
| python_startup             | 11.7 ms                                                      | 10.8 ms: 1.08x faster                                        |
| scimark_fft                | 303 ms                                                       | 281 ms: 1.08x faster                                         |
| float                      | 81.6 ms                                                      | 76.0 ms: 1.07x faster                                        |
| bench_mp_pool              | 4.96 ms                                                      | 4.63 ms: 1.07x faster                                        |
| regex_dna                  | 240 ms                                                       | 226 ms: 1.06x faster                                         |
| xml_etree_generate         | 85.3 ms                                                      | 80.5 ms: 1.06x faster                                        |
| regex_effbot               | 3.61 ms                                                      | 3.42 ms: 1.06x faster                                        |
| pidigits                   | 264 ms                                                       | 251 ms: 1.05x faster                                         |
| unpickle_list              | 4.65 us                                                      | 4.47 us: 1.04x faster                                        |
| xml_etree_process          | 58.3 ms                                                      | 56.1 ms: 1.04x faster                                        |
| sqlalchemy_declarative     | 161 ms                                                       | 155 ms: 1.04x faster                                         |
| pprint_safe_repr           | 808 ms                                                       | 780 ms: 1.04x faster                                         |
| telco                      | 7.16 ms                                                      | 6.91 ms: 1.04x faster                                        |
| aiohttp                    | 1.02 ms                                                      | 984 us: 1.03x faster                                         |
| regex_v8                   | 24.4 ms                                                      | 23.7 ms: 1.03x faster                                        |
| pickle                     | 10.0 us                                                      | 9.77 us: 1.03x faster                                        |
| gunicorn                   | 1.01 ms                                                      | 986 us: 1.02x faster                                         |
| deepcopy_reduce            | 3.41 us                                                      | 3.37 us: 1.01x faster                                        |
| pycparser                  | 1.29 sec                                                     | 1.28 sec: 1.01x faster                                       |
| docutils                   | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                       |
| crypto_pyaes               | 82.4 ms                                                      | 81.8 ms: 1.01x faster                                        |
| pickle_dict                | 32.0 us                                                      | 31.8 us: 1.01x faster                                        |
| pprint_pformat             | 1.64 sec                                                     | 1.63 sec: 1.01x faster                                       |
| pickle_pure_python         | 319 us                                                       | 318 us: 1.00x faster                                         |
| 2to3                       | 285 ms                                                       | 286 ms: 1.00x slower                                         |
| sqlglot_optimize           | 58.4 ms                                                      | 59.2 ms: 1.01x slower                                        |
| scimark_monte_carlo        | 69.5 ms                                                      | 70.6 ms: 1.01x slower                                        |
| deepcopy_memo              | 36.6 us                                                      | 37.3 us: 1.02x slower                                        |
| pathlib                    | 18.7 ms                                                      | 19.1 ms: 1.02x slower                                        |
| chameleon                  | 7.27 ms                                                      | 7.42 ms: 1.02x slower                                        |
| sqlglot_normalize          | 119 ms                                                       | 122 ms: 1.02x slower                                         |
| raytrace                   | 301 ms                                                       | 308 ms: 1.02x slower                                         |
| xml_etree_iterparse        | 104 ms                                                       | 106 ms: 1.02x slower                                         |
| pyflate                    | 442 ms                                                       | 453 ms: 1.02x slower                                         |
| scimark_sor                | 107 ms                                                       | 109 ms: 1.02x slower                                         |
| tornado_http               | 122 ms                                                       | 125 ms: 1.02x slower                                         |
| meteor_contest             | 126 ms                                                       | 130 ms: 1.03x slower                                         |
| django_template            | 38.7 ms                                                      | 40.4 ms: 1.04x slower                                        |
| deepcopy                   | 371 us                                                       | 389 us: 1.05x slower                                         |
| tomli_loads                | 2.17 sec                                                     | 2.27 sec: 1.05x slower                                       |
| dulwich_log                | 64.9 ms                                                      | 68.3 ms: 1.05x slower                                        |
| dask                       | 394 ms                                                       | 417 ms: 1.06x slower                                         |
| mdp                        | 2.56 sec                                                     | 2.72 sec: 1.06x slower                                       |
| bench_thread_pool          | 956 us                                                       | 1.02 ms: 1.07x slower                                        |
| sympy_integrate            | 24.0 ms                                                      | 25.6 ms: 1.07x slower                                        |
| sqlalchemy_imperative      | 18.6 ms                                                      | 19.9 ms: 1.07x slower                                        |
| logging_format             | 7.29 us                                                      | 7.83 us: 1.07x slower                                        |
| sqlglot_transpile          | 1.80 ms                                                      | 1.94 ms: 1.07x slower                                        |
| async_tree_cpu_io_mixed_tg | 706 ms                                                       | 760 ms: 1.08x slower                                         |
| xml_etree_parse            | 147 ms                                                       | 159 ms: 1.08x slower                                         |
| json                       | 5.17 ms                                                      | 5.59 ms: 1.08x slower                                        |
| async_tree_cpu_io_mixed    | 704 ms                                                       | 762 ms: 1.08x slower                                         |
| nbody                      | 88.2 ms                                                      | 95.8 ms: 1.09x slower                                        |
| logging_simple             | 6.64 us                                                      | 7.21 us: 1.09x slower                                        |
| regex_compile              | 145 ms                                                       | 157 ms: 1.09x slower                                         |
| mako                       | 10.1 ms                                                      | 11.0 ms: 1.09x slower                                        |
| async_tree_memoization_tg  | 554 ms                                                       | 605 ms: 1.09x slower                                         |
| logging_silent             | 93.3 ns                                                      | 102 ns: 1.09x slower                                         |
| async_tree_io_tg           | 1.07 sec                                                     | 1.17 sec: 1.09x slower                                       |
| async_tree_none_tg         | 440 ms                                                       | 482 ms: 1.10x slower                                         |
| gc_traversal               | 3.70 ms                                                      | 4.06 ms: 1.10x slower                                        |
| sympy_str                  | 305 ms                                                       | 336 ms: 1.10x slower                                         |
| nqueens                    | 90.1 ms                                                      | 99.2 ms: 1.10x slower                                        |
| sqlglot_parse              | 1.41 ms                                                      | 1.55 ms: 1.10x slower                                        |
| richards                   | 45.1 ms                                                      | 49.9 ms: 1.11x slower                                        |
| go                         | 149 ms                                                       | 166 ms: 1.11x slower                                         |
| chaos                      | 64.1 ms                                                      | 71.6 ms: 1.12x slower                                        |
| sympy_expand               | 492 ms                                                       | 550 ms: 1.12x slower                                         |
| async_tree_io              | 1.06 sec                                                     | 1.19 sec: 1.13x slower                                       |
| unpickle_pure_python       | 210 us                                                       | 236 us: 1.13x slower                                         |
| sympy_sum                  | 163 ms                                                       | 184 ms: 1.13x slower                                         |
| comprehensions             | 21.8 us                                                      | 24.8 us: 1.14x slower                                        |
| async_tree_none            | 459 ms                                                       | 529 ms: 1.15x slower                                         |
| hexiom                     | 5.97 ms                                                      | 6.97 ms: 1.17x slower                                        |
| scimark_lu                 | 98.6 ms                                                      | 115 ms: 1.17x slower                                         |
| async_tree_memoization     | 554 ms                                                       | 648 ms: 1.17x slower                                         |
| json_loads                 | 24.3 us                                                      | 29.0 us: 1.19x slower                                        |
| coroutines                 | 23.1 ms                                                      | 27.9 ms: 1.21x slower                                        |
| mypy2                      | 365 ms                                                       | 449 ms: 1.23x slower                                         |
| deltablue                  | 3.24 ms                                                      | 4.03 ms: 1.24x slower                                        |
| fannkuch                   | 362 ms                                                       | 457 ms: 1.26x slower                                         |
| richards_super             | 50.8 ms                                                      | 65.2 ms: 1.28x slower                                        |
| json_dumps                 | 10.3 ms                                                      | 13.5 ms: 1.31x slower                                        |
| generators                 | 37.3 ms                                                      | 56.4 ms: 1.51x slower                                        |
| asyncio_tcp_ssl            | 1.57 sec                                                     | 3.09 sec: 1.96x slower                                       |
| asyncio_tcp                | 380 ms                                                       | 752 ms: 1.98x slower                                         |
| typing_runtime_protocols   | 150 us                                                       | 527 us: 3.51x slower                                         |
| Geometric mean             | (ref)                                                        | 1.07x slower                                                 |

Benchmark hidden because not significant (4): spectral_norm, coverage, asyncio_websockets, create_gc_cycles
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
