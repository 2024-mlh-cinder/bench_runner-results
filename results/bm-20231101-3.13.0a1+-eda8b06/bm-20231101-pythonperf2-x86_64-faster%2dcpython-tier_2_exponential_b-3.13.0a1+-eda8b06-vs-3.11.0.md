
# Results vs. 3.11.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: eda8b06
- commit date: 2023-11-01
- overall geometric mean: 1.00x faster
- HPT reliability: 58.33%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 308 ms: 1.08x slower                                                                   |
| docutils       | 2.87 sec                                                     | 2.94 sec: 1.03x slower                                                                 |
| tornado_http   | 125 ms                                                       | 123 ms: 1.01x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                           |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 447 ms: 1.18x faster                                                                   |
| async_tree_memoization     | 648 ms                                                       | 562 ms: 1.15x faster                                                                   |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.08x faster                                                                 |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 712 ms: 1.07x faster                                                                   |
| async_tree_memoization_tg  | 605 ms                                                       | 573 ms: 1.06x faster                                                                   |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.05x faster                                                                 |
| async_tree_none_tg         | 482 ms                                                       | 460 ms: 1.05x faster                                                                   |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 731 ms: 1.04x faster                                                                   |
| Geometric mean             | (ref)                                                        | 1.08x faster                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 265 ms: 1.06x slower                                                                   |
| nbody          | 95.8 ms                                                      | 110 ms: 1.15x slower                                                                   |
| float          | 76.0 ms                                                      | 103 ms: 1.36x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.18x slower                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.47 ms: 1.02x slower                                                                  |
| regex_v8       | 23.7 ms                                                      | 24.5 ms: 1.03x slower                                                                  |
| regex_dna      | 226 ms                                                       | 243 ms: 1.07x slower                                                                   |
| regex_compile  | 157 ms                                                       | 174 ms: 1.11x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.06x slower                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.6 ms: 1.26x faster                                                                  |
| json_loads           | 29.0 us                                                      | 24.5 us: 1.18x faster                                                                  |
| xml_etree_parse      | 159 ms                                                       | 149 ms: 1.06x faster                                                                   |
| pickle_pure_python   | 318 us                                                       | 315 us: 1.01x faster                                                                   |
| pickle_dict          | 31.8 us                                                      | 32.0 us: 1.01x slower                                                                  |
| pickle               | 9.77 us                                                      | 9.98 us: 1.02x slower                                                                  |
| unpickle_list        | 4.47 us                                                      | 4.61 us: 1.03x slower                                                                  |
| xml_etree_iterparse  | 106 ms                                                       | 110 ms: 1.04x slower                                                                   |
| xml_etree_process    | 56.1 ms                                                      | 58.9 ms: 1.05x slower                                                                  |
| unpickle_pure_python | 236 us                                                       | 248 us: 1.05x slower                                                                   |
| xml_etree_generate   | 80.5 ms                                                      | 86.6 ms: 1.08x slower                                                                  |
| pickle_list          | 3.89 us                                                      | 4.24 us: 1.09x slower                                                                  |
| unpickle             | 13.2 us                                                      | 14.4 us: 1.09x slower                                                                  |
| tomli_loads          | 2.27 sec                                                     | 2.78 sec: 1.22x slower                                                                 |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                                  |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 14.3 ms: 1.30x slower                                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231101-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-eda8b06 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 131 us: 4.01x faster                                                                   |
| asyncio_tcp                | 752 ms                                                       | 371 ms: 2.03x faster                                                                   |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.60 sec: 1.94x faster                                                                 |
| generators                 | 56.4 ms                                                      | 35.3 ms: 1.60x faster                                                                  |
| json_dumps                 | 13.5 ms                                                      | 10.6 ms: 1.26x faster                                                                  |
| coroutines                 | 27.9 ms                                                      | 22.7 ms: 1.23x faster                                                                  |
| json_loads                 | 29.0 us                                                      | 24.5 us: 1.18x faster                                                                  |
| async_tree_none            | 529 ms                                                       | 447 ms: 1.18x faster                                                                   |
| mypy2                      | 449 ms                                                       | 381 ms: 1.18x faster                                                                   |
| sympy_sum                  | 184 ms                                                       | 157 ms: 1.17x faster                                                                   |
| async_tree_memoization     | 648 ms                                                       | 562 ms: 1.15x faster                                                                   |
| richards_super             | 65.2 ms                                                      | 59.1 ms: 1.10x faster                                                                  |
| sympy_str                  | 336 ms                                                       | 306 ms: 1.10x faster                                                                   |
| scimark_lu                 | 115 ms                                                       | 106 ms: 1.09x faster                                                                   |
| gc_traversal               | 4.06 ms                                                      | 3.74 ms: 1.09x faster                                                                  |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.08x faster                                                                 |
| fannkuch                   | 457 ms                                                       | 425 ms: 1.08x faster                                                                   |
| json                       | 5.59 ms                                                      | 5.20 ms: 1.07x faster                                                                  |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 712 ms: 1.07x faster                                                                   |
| logging_format             | 7.83 us                                                      | 7.35 us: 1.06x faster                                                                  |
| xml_etree_parse            | 159 ms                                                       | 149 ms: 1.06x faster                                                                   |
| sqlglot_parse              | 1.55 ms                                                      | 1.46 ms: 1.06x faster                                                                  |
| sympy_expand               | 550 ms                                                       | 519 ms: 1.06x faster                                                                   |
| crypto_pyaes               | 81.8 ms                                                      | 77.2 ms: 1.06x faster                                                                  |
| async_tree_memoization_tg  | 605 ms                                                       | 573 ms: 1.06x faster                                                                   |
| logging_simple             | 7.21 us                                                      | 6.86 us: 1.05x faster                                                                  |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.05x faster                                                                 |
| async_tree_none_tg         | 482 ms                                                       | 460 ms: 1.05x faster                                                                   |
| chaos                      | 71.6 ms                                                      | 68.4 ms: 1.05x faster                                                                  |
| sqlglot_normalize          | 122 ms                                                       | 117 ms: 1.04x faster                                                                   |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 731 ms: 1.04x faster                                                                   |
| sympy_integrate            | 25.6 ms                                                      | 24.6 ms: 1.04x faster                                                                  |
| logging_silent             | 102 ns                                                       | 98.5 ns: 1.04x faster                                                                  |
| bench_thread_pool          | 1.02 ms                                                      | 985 us: 1.04x faster                                                                   |
| sqlglot_transpile          | 1.94 ms                                                      | 1.88 ms: 1.03x faster                                                                  |
| mdp                        | 2.72 sec                                                     | 2.64 sec: 1.03x faster                                                                 |
| bench_mp_pool              | 4.63 ms                                                      | 4.50 ms: 1.03x faster                                                                  |
| spectral_norm              | 94.0 ms                                                      | 91.5 ms: 1.03x faster                                                                  |
| deepcopy                   | 389 us                                                       | 379 us: 1.03x faster                                                                   |
| tornado_http               | 125 ms                                                       | 123 ms: 1.01x faster                                                                   |
| raytrace                   | 308 ms                                                       | 303 ms: 1.01x faster                                                                   |
| pickle_pure_python         | 318 us                                                       | 315 us: 1.01x faster                                                                   |
| pickle_dict                | 31.8 us                                                      | 32.0 us: 1.01x slower                                                                  |
| sqlglot_optimize           | 59.2 ms                                                      | 59.9 ms: 1.01x slower                                                                  |
| regex_effbot               | 3.42 ms                                                      | 3.47 ms: 1.02x slower                                                                  |
| pickle                     | 9.77 us                                                      | 9.98 us: 1.02x slower                                                                  |
| docutils                   | 2.87 sec                                                     | 2.94 sec: 1.03x slower                                                                 |
| unpickle_list              | 4.47 us                                                      | 4.61 us: 1.03x slower                                                                  |
| dulwich_log                | 68.3 ms                                                      | 70.5 ms: 1.03x slower                                                                  |
| regex_v8                   | 23.7 ms                                                      | 24.5 ms: 1.03x slower                                                                  |
| xml_etree_iterparse        | 106 ms                                                       | 110 ms: 1.04x slower                                                                   |
| meteor_contest             | 130 ms                                                       | 136 ms: 1.04x slower                                                                   |
| xml_etree_process          | 56.1 ms                                                      | 58.9 ms: 1.05x slower                                                                  |
| unpickle_pure_python       | 236 us                                                       | 248 us: 1.05x slower                                                                   |
| comprehensions             | 24.8 us                                                      | 26.1 us: 1.05x slower                                                                  |
| pathlib                    | 19.1 ms                                                      | 20.2 ms: 1.05x slower                                                                  |
| pidigits                   | 251 ms                                                       | 265 ms: 1.06x slower                                                                   |
| richards                   | 49.9 ms                                                      | 53.2 ms: 1.07x slower                                                                  |
| pycparser                  | 1.28 sec                                                     | 1.37 sec: 1.07x slower                                                                 |
| scimark_monte_carlo        | 70.6 ms                                                      | 75.3 ms: 1.07x slower                                                                  |
| regex_dna                  | 226 ms                                                       | 243 ms: 1.07x slower                                                                   |
| xml_etree_generate         | 80.5 ms                                                      | 86.6 ms: 1.08x slower                                                                  |
| 2to3                       | 286 ms                                                       | 308 ms: 1.08x slower                                                                   |
| sqlite_synth               | 2.49 us                                                      | 2.70 us: 1.09x slower                                                                  |
| pickle_list                | 3.89 us                                                      | 4.24 us: 1.09x slower                                                                  |
| unpickle                   | 13.2 us                                                      | 14.4 us: 1.09x slower                                                                  |
| go                         | 166 ms                                                       | 182 ms: 1.10x slower                                                                   |
| regex_compile              | 157 ms                                                       | 174 ms: 1.11x slower                                                                   |
| unpack_sequence            | 44.9 ns                                                      | 50.7 ns: 1.13x slower                                                                  |
| nqueens                    | 99.2 ms                                                      | 112 ms: 1.13x slower                                                                   |
| deepcopy_memo              | 37.3 us                                                      | 42.4 us: 1.14x slower                                                                  |
| pprint_pformat             | 1.63 sec                                                     | 1.86 sec: 1.14x slower                                                                 |
| nbody                      | 95.8 ms                                                      | 110 ms: 1.15x slower                                                                   |
| pprint_safe_repr           | 780 ms                                                       | 906 ms: 1.16x slower                                                                   |
| telco                      | 6.91 ms                                                      | 8.15 ms: 1.18x slower                                                                  |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                                  |
| async_generators           | 322 ms                                                       | 383 ms: 1.19x slower                                                                   |
| pyflate                    | 453 ms                                                       | 545 ms: 1.20x slower                                                                   |
| coverage                   | 66.6 ms                                                      | 80.2 ms: 1.20x slower                                                                  |
| scimark_fft                | 281 ms                                                       | 343 ms: 1.22x slower                                                                   |
| tomli_loads                | 2.27 sec                                                     | 2.78 sec: 1.22x slower                                                                 |
| mako                       | 11.0 ms                                                      | 14.3 ms: 1.30x slower                                                                  |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 5.30 ms: 1.31x slower                                                                  |
| deltablue                  | 4.03 ms                                                      | 5.41 ms: 1.34x slower                                                                  |
| float                      | 76.0 ms                                                      | 103 ms: 1.36x slower                                                                   |
| scimark_sor                | 109 ms                                                       | 152 ms: 1.39x slower                                                                   |
| hexiom                     | 6.97 ms                                                      | 9.99 ms: 1.43x slower                                                                  |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                                  |
| Geometric mean             | (ref)                                                        | 1.00x faster                                                                           |

Benchmark hidden because not significant (4): asyncio_websockets, deepcopy_reduce, chameleon, create_gc_cycles
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 58.33% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
