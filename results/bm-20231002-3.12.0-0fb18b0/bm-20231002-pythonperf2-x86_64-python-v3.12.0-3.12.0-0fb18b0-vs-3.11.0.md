
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0
- machine: linux-x86_64
- commit hash: 0fb18b0
- commit date: 2023-10-02
- overall geometric mean: 1.07x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 285 ms: 1.00x faster                                         |
| chameleon      | 7.42 ms                                                      | 7.27 ms: 1.02x faster                                        |
| docutils       | 2.87 sec                                                     | 2.89 sec: 1.01x slower                                       |
| tornado_http   | 125 ms                                                       | 122 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_memoization     | 648 ms                                                       | 554 ms: 1.17x faster                                         |
| async_tree_none            | 529 ms                                                       | 459 ms: 1.15x faster                                         |
| async_tree_io              | 1.19 sec                                                     | 1.06 sec: 1.13x faster                                       |
| async_tree_none_tg         | 482 ms                                                       | 440 ms: 1.10x faster                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.07 sec: 1.09x faster                                       |
| async_tree_memoization_tg  | 605 ms                                                       | 554 ms: 1.09x faster                                         |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 704 ms: 1.08x faster                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 706 ms: 1.08x faster                                         |
| Geometric mean             | (ref)                                                        | 1.11x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 95.8 ms                                                      | 88.2 ms: 1.09x faster                                        |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                         |
| float          | 76.0 ms                                                      | 81.6 ms: 1.07x slower                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 157 ms                                                       | 145 ms: 1.09x faster                                         |
| regex_v8       | 23.7 ms                                                      | 24.4 ms: 1.03x slower                                        |
| regex_effbot   | 3.42 ms                                                      | 3.61 ms: 1.06x slower                                        |
| regex_dna      | 226 ms                                                       | 240 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                        | 1.02x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.3 ms: 1.31x faster                                        |
| json_loads           | 29.0 us                                                      | 24.3 us: 1.19x faster                                        |
| unpickle_pure_python | 236 us                                                       | 210 us: 1.13x faster                                         |
| xml_etree_parse      | 159 ms                                                       | 147 ms: 1.08x faster                                         |
| tomli_loads          | 2.27 sec                                                     | 2.17 sec: 1.05x faster                                       |
| xml_etree_iterparse  | 106 ms                                                       | 104 ms: 1.02x faster                                         |
| pickle_pure_python   | 318 us                                                       | 319 us: 1.00x slower                                         |
| pickle_dict          | 31.8 us                                                      | 32.0 us: 1.01x slower                                        |
| pickle               | 9.77 us                                                      | 10.0 us: 1.03x slower                                        |
| xml_etree_process    | 56.1 ms                                                      | 58.3 ms: 1.04x slower                                        |
| unpickle_list        | 4.47 us                                                      | 4.65 us: 1.04x slower                                        |
| xml_etree_generate   | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                        |
| pickle_list          | 3.89 us                                                      | 4.22 us: 1.08x slower                                        |
| unpickle             | 13.2 us                                                      | 15.3 us: 1.16x slower                                        |
| Geometric mean       | (ref)                                                        | 1.02x faster                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.08x slower                                        |
| python_startup_no_site | 7.78 ms                                                      | 8.67 ms: 1.11x slower                                        |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako            | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                        |
| django_template | 40.4 ms                                                      | 38.7 ms: 1.04x faster                                        |
| Geometric mean  | (ref)                                                        | 1.07x faster                                                 |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 150 us: 3.51x faster                                         |
| asyncio_tcp                | 752 ms                                                       | 380 ms: 1.98x faster                                         |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.57 sec: 1.96x faster                                       |
| generators                 | 56.4 ms                                                      | 37.3 ms: 1.51x faster                                        |
| json_dumps                 | 13.5 ms                                                      | 10.3 ms: 1.31x faster                                        |
| richards_super             | 65.2 ms                                                      | 50.8 ms: 1.28x faster                                        |
| fannkuch                   | 457 ms                                                       | 362 ms: 1.26x faster                                         |
| deltablue                  | 4.03 ms                                                      | 3.24 ms: 1.24x faster                                        |
| mypy2                      | 449 ms                                                       | 365 ms: 1.23x faster                                         |
| coroutines                 | 27.9 ms                                                      | 23.1 ms: 1.21x faster                                        |
| json_loads                 | 29.0 us                                                      | 24.3 us: 1.19x faster                                        |
| async_tree_memoization     | 648 ms                                                       | 554 ms: 1.17x faster                                         |
| scimark_lu                 | 115 ms                                                       | 98.6 ms: 1.17x faster                                        |
| hexiom                     | 6.97 ms                                                      | 5.97 ms: 1.17x faster                                        |
| async_tree_none            | 529 ms                                                       | 459 ms: 1.15x faster                                         |
| comprehensions             | 24.8 us                                                      | 21.8 us: 1.14x faster                                        |
| sympy_sum                  | 184 ms                                                       | 163 ms: 1.13x faster                                         |
| unpickle_pure_python       | 236 us                                                       | 210 us: 1.13x faster                                         |
| async_tree_io              | 1.19 sec                                                     | 1.06 sec: 1.13x faster                                       |
| sympy_expand               | 550 ms                                                       | 492 ms: 1.12x faster                                         |
| chaos                      | 71.6 ms                                                      | 64.1 ms: 1.12x faster                                        |
| go                         | 166 ms                                                       | 149 ms: 1.11x faster                                         |
| richards                   | 49.9 ms                                                      | 45.1 ms: 1.11x faster                                        |
| sqlglot_parse              | 1.55 ms                                                      | 1.41 ms: 1.10x faster                                        |
| nqueens                    | 99.2 ms                                                      | 90.1 ms: 1.10x faster                                        |
| sympy_str                  | 336 ms                                                       | 305 ms: 1.10x faster                                         |
| gc_traversal               | 4.06 ms                                                      | 3.70 ms: 1.10x faster                                        |
| async_tree_none_tg         | 482 ms                                                       | 440 ms: 1.10x faster                                         |
| async_tree_io_tg           | 1.17 sec                                                     | 1.07 sec: 1.09x faster                                       |
| logging_silent             | 102 ns                                                       | 93.3 ns: 1.09x faster                                        |
| async_tree_memoization_tg  | 605 ms                                                       | 554 ms: 1.09x faster                                         |
| mako                       | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                        |
| regex_compile              | 157 ms                                                       | 145 ms: 1.09x faster                                         |
| logging_simple             | 7.21 us                                                      | 6.64 us: 1.09x faster                                        |
| nbody                      | 95.8 ms                                                      | 88.2 ms: 1.09x faster                                        |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 704 ms: 1.08x faster                                         |
| json                       | 5.59 ms                                                      | 5.17 ms: 1.08x faster                                        |
| xml_etree_parse            | 159 ms                                                       | 147 ms: 1.08x faster                                         |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 706 ms: 1.08x faster                                         |
| sqlglot_transpile          | 1.94 ms                                                      | 1.80 ms: 1.07x faster                                        |
| logging_format             | 7.83 us                                                      | 7.29 us: 1.07x faster                                        |
| sqlalchemy_imperative      | 19.9 ms                                                      | 18.6 ms: 1.07x faster                                        |
| sympy_integrate            | 25.6 ms                                                      | 24.0 ms: 1.07x faster                                        |
| bench_thread_pool          | 1.02 ms                                                      | 956 us: 1.07x faster                                         |
| mdp                        | 2.72 sec                                                     | 2.56 sec: 1.06x faster                                       |
| dask                       | 417 ms                                                       | 394 ms: 1.06x faster                                         |
| dulwich_log                | 68.3 ms                                                      | 64.9 ms: 1.05x faster                                        |
| tomli_loads                | 2.27 sec                                                     | 2.17 sec: 1.05x faster                                       |
| deepcopy                   | 389 us                                                       | 371 us: 1.05x faster                                         |
| django_template            | 40.4 ms                                                      | 38.7 ms: 1.04x faster                                        |
| meteor_contest             | 130 ms                                                       | 126 ms: 1.03x faster                                         |
| tornado_http               | 125 ms                                                       | 122 ms: 1.02x faster                                         |
| scimark_sor                | 109 ms                                                       | 107 ms: 1.02x faster                                         |
| pyflate                    | 453 ms                                                       | 442 ms: 1.02x faster                                         |
| xml_etree_iterparse        | 106 ms                                                       | 104 ms: 1.02x faster                                         |
| raytrace                   | 308 ms                                                       | 301 ms: 1.02x faster                                         |
| sqlglot_normalize          | 122 ms                                                       | 119 ms: 1.02x faster                                         |
| chameleon                  | 7.42 ms                                                      | 7.27 ms: 1.02x faster                                        |
| pathlib                    | 19.1 ms                                                      | 18.7 ms: 1.02x faster                                        |
| deepcopy_memo              | 37.3 us                                                      | 36.6 us: 1.02x faster                                        |
| scimark_monte_carlo        | 70.6 ms                                                      | 69.5 ms: 1.01x faster                                        |
| sqlglot_optimize           | 59.2 ms                                                      | 58.4 ms: 1.01x faster                                        |
| 2to3                       | 286 ms                                                       | 285 ms: 1.00x faster                                         |
| pickle_pure_python         | 318 us                                                       | 319 us: 1.00x slower                                         |
| pprint_pformat             | 1.63 sec                                                     | 1.64 sec: 1.01x slower                                       |
| pickle_dict                | 31.8 us                                                      | 32.0 us: 1.01x slower                                        |
| crypto_pyaes               | 81.8 ms                                                      | 82.4 ms: 1.01x slower                                        |
| docutils                   | 2.87 sec                                                     | 2.89 sec: 1.01x slower                                       |
| pycparser                  | 1.28 sec                                                     | 1.29 sec: 1.01x slower                                       |
| deepcopy_reduce            | 3.37 us                                                      | 3.41 us: 1.01x slower                                        |
| gunicorn                   | 986 us                                                       | 1.01 ms: 1.02x slower                                        |
| pickle                     | 9.77 us                                                      | 10.0 us: 1.03x slower                                        |
| regex_v8                   | 23.7 ms                                                      | 24.4 ms: 1.03x slower                                        |
| aiohttp                    | 984 us                                                       | 1.02 ms: 1.03x slower                                        |
| telco                      | 6.91 ms                                                      | 7.16 ms: 1.04x slower                                        |
| pprint_safe_repr           | 780 ms                                                       | 808 ms: 1.04x slower                                         |
| sqlalchemy_declarative     | 155 ms                                                       | 161 ms: 1.04x slower                                         |
| xml_etree_process          | 56.1 ms                                                      | 58.3 ms: 1.04x slower                                        |
| unpickle_list              | 4.47 us                                                      | 4.65 us: 1.04x slower                                        |
| pidigits                   | 251 ms                                                       | 264 ms: 1.05x slower                                         |
| regex_effbot               | 3.42 ms                                                      | 3.61 ms: 1.06x slower                                        |
| xml_etree_generate         | 80.5 ms                                                      | 85.3 ms: 1.06x slower                                        |
| regex_dna                  | 226 ms                                                       | 240 ms: 1.06x slower                                         |
| bench_mp_pool              | 4.63 ms                                                      | 4.96 ms: 1.07x slower                                        |
| float                      | 76.0 ms                                                      | 81.6 ms: 1.07x slower                                        |
| scimark_fft                | 281 ms                                                       | 303 ms: 1.08x slower                                         |
| python_startup             | 10.8 ms                                                      | 11.7 ms: 1.08x slower                                        |
| pickle_list                | 3.89 us                                                      | 4.22 us: 1.08x slower                                        |
| sqlite_synth               | 2.49 us                                                      | 2.72 us: 1.09x slower                                        |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 4.49 ms: 1.11x slower                                        |
| python_startup_no_site     | 7.78 ms                                                      | 8.67 ms: 1.11x slower                                        |
| unpickle                   | 13.2 us                                                      | 15.3 us: 1.16x slower                                        |
| async_generators           | 322 ms                                                       | 385 ms: 1.20x slower                                         |
| unpack_sequence            | 44.9 ns                                                      | 54.5 ns: 1.21x slower                                        |
| Geometric mean             | (ref)                                                        | 1.07x faster                                                 |

Benchmark hidden because not significant (4): create_gc_cycles, asyncio_websockets, coverage, spectral_norm
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
