
# Results vs. 3.11.0

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: bf453f8
- commit date: 2023-11-02
- overall geometric mean: 1.01x faster \*
- HPT reliability: 55.57%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 308 ms: 1.08x slower                                                                   |
| chameleon      | 7.42 ms                                                      | 7.72 ms: 1.04x slower                                                                  |
| docutils       | 2.87 sec                                                     | 2.95 sec: 1.03x slower                                                                 |
| tornado_http   | 125 ms                                                       | 123 ms: 1.02x faster                                                                   |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none            | 529 ms                                                       | 450 ms: 1.18x faster                                                                   |
| async_tree_memoization     | 648 ms                                                       | 565 ms: 1.15x faster                                                                   |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.08x faster                                                                 |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 720 ms: 1.06x faster                                                                   |
| async_tree_none_tg         | 482 ms                                                       | 458 ms: 1.05x faster                                                                   |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.05x faster                                                                 |
| async_tree_memoization_tg  | 605 ms                                                       | 578 ms: 1.05x faster                                                                   |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 735 ms: 1.03x faster                                                                   |
| Geometric mean             | (ref)                                                        | 1.08x faster                                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 266 ms: 1.06x slower                                                                   |
| nbody          | 95.8 ms                                                      | 115 ms: 1.20x slower                                                                   |
| float          | 76.0 ms                                                      | 103 ms: 1.35x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.20x slower                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.48 ms: 1.02x slower                                                                  |
| regex_v8       | 23.7 ms                                                      | 25.8 ms: 1.09x slower                                                                  |
| regex_dna      | 226 ms                                                       | 247 ms: 1.09x slower                                                                   |
| regex_compile  | 157 ms                                                       | 174 ms: 1.11x slower                                                                   |
| Geometric mean | (ref)                                                        | 1.08x slower                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                      | 10.5 ms: 1.28x faster                                                                  |
| json_loads           | 29.0 us                                                      | 24.3 us: 1.19x faster                                                                  |
| xml_etree_parse      | 159 ms                                                       | 152 ms: 1.04x faster                                                                   |
| pickle_pure_python   | 318 us                                                       | 324 us: 1.02x slower                                                                   |
| pickle               | 9.77 us                                                      | 10.0 us: 1.03x slower                                                                  |
| unpickle_pure_python | 236 us                                                       | 243 us: 1.03x slower                                                                   |
| xml_etree_process    | 56.1 ms                                                      | 59.1 ms: 1.05x slower                                                                  |
| unpickle_list        | 4.47 us                                                      | 4.75 us: 1.06x slower                                                                  |
| xml_etree_iterparse  | 106 ms                                                       | 113 ms: 1.07x slower                                                                   |
| xml_etree_generate   | 80.5 ms                                                      | 86.9 ms: 1.08x slower                                                                  |
| pickle_list          | 3.89 us                                                      | 4.23 us: 1.09x slower                                                                  |
| unpickle             | 13.2 us                                                      | 14.6 us: 1.11x slower                                                                  |
| tomli_loads          | 2.27 sec                                                     | 2.83 sec: 1.24x slower                                                                 |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                           |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                                  |
| python_startup_no_site | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                                  |
| Geometric mean         | (ref)                                                        | 1.32x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 14.2 ms: 1.29x slower                                                                  |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231102-pythonperf2-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-bf453f8 |
|----------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| typing_runtime_protocols   | 527 us                                                       | 132 us: 3.98x faster                                                                   |
| asyncio_tcp                | 752 ms                                                       | 373 ms: 2.02x faster                                                                   |
| asyncio_tcp_ssl            | 3.09 sec                                                     | 1.59 sec: 1.94x faster                                                                 |
| generators                 | 56.4 ms                                                      | 37.0 ms: 1.52x faster                                                                  |
| json_dumps                 | 13.5 ms                                                      | 10.5 ms: 1.28x faster                                                                  |
| coroutines                 | 27.9 ms                                                      | 22.6 ms: 1.23x faster                                                                  |
| json_loads                 | 29.0 us                                                      | 24.3 us: 1.19x faster                                                                  |
| mypy2                      | 449 ms                                                       | 381 ms: 1.18x faster                                                                   |
| sympy_sum                  | 184 ms                                                       | 157 ms: 1.18x faster                                                                   |
| async_tree_none            | 529 ms                                                       | 450 ms: 1.18x faster                                                                   |
| async_tree_memoization     | 648 ms                                                       | 565 ms: 1.15x faster                                                                   |
| unpack_sequence            | 44.9 ns                                                      | 40.5 ns: 1.11x faster                                                                  |
| scimark_lu                 | 115 ms                                                       | 104 ms: 1.10x faster                                                                   |
| sympy_str                  | 336 ms                                                       | 306 ms: 1.10x faster                                                                   |
| fannkuch                   | 457 ms                                                       | 417 ms: 1.10x faster                                                                   |
| raytrace                   | 308 ms                                                       | 283 ms: 1.09x faster                                                                   |
| richards_super             | 65.2 ms                                                      | 60.1 ms: 1.08x faster                                                                  |
| async_tree_io              | 1.19 sec                                                     | 1.10 sec: 1.08x faster                                                                 |
| crypto_pyaes               | 81.8 ms                                                      | 75.9 ms: 1.08x faster                                                                  |
| sqlglot_parse              | 1.55 ms                                                      | 1.45 ms: 1.07x faster                                                                  |
| json                       | 5.59 ms                                                      | 5.24 ms: 1.07x faster                                                                  |
| async_tree_cpu_io_mixed    | 762 ms                                                       | 720 ms: 1.06x faster                                                                   |
| sympy_expand               | 550 ms                                                       | 521 ms: 1.06x faster                                                                   |
| chaos                      | 71.6 ms                                                      | 67.8 ms: 1.06x faster                                                                  |
| async_tree_none_tg         | 482 ms                                                       | 458 ms: 1.05x faster                                                                   |
| async_tree_io_tg           | 1.17 sec                                                     | 1.12 sec: 1.05x faster                                                                 |
| async_tree_memoization_tg  | 605 ms                                                       | 578 ms: 1.05x faster                                                                   |
| xml_etree_parse            | 159 ms                                                       | 152 ms: 1.04x faster                                                                   |
| sympy_integrate            | 25.6 ms                                                      | 24.6 ms: 1.04x faster                                                                  |
| logging_simple             | 7.21 us                                                      | 6.94 us: 1.04x faster                                                                  |
| sqlglot_transpile          | 1.94 ms                                                      | 1.87 ms: 1.04x faster                                                                  |
| sqlglot_normalize          | 122 ms                                                       | 118 ms: 1.04x faster                                                                   |
| bench_thread_pool          | 1.02 ms                                                      | 985 us: 1.04x faster                                                                   |
| async_tree_cpu_io_mixed_tg | 760 ms                                                       | 735 ms: 1.03x faster                                                                   |
| spectral_norm              | 94.0 ms                                                      | 91.1 ms: 1.03x faster                                                                  |
| gc_traversal               | 4.06 ms                                                      | 3.95 ms: 1.03x faster                                                                  |
| logging_silent             | 102 ns                                                       | 99.2 ns: 1.03x faster                                                                  |
| logging_format             | 7.83 us                                                      | 7.62 us: 1.03x faster                                                                  |
| deepcopy                   | 389 us                                                       | 380 us: 1.02x faster                                                                   |
| tornado_http               | 125 ms                                                       | 123 ms: 1.02x faster                                                                   |
| deepcopy_reduce            | 3.37 us                                                      | 3.32 us: 1.02x faster                                                                  |
| mdp                        | 2.72 sec                                                     | 2.69 sec: 1.01x faster                                                                 |
| sqlglot_optimize           | 59.2 ms                                                      | 60.0 ms: 1.01x slower                                                                  |
| comprehensions             | 24.8 us                                                      | 25.3 us: 1.02x slower                                                                  |
| scimark_monte_carlo        | 70.6 ms                                                      | 71.8 ms: 1.02x slower                                                                  |
| pickle_pure_python         | 318 us                                                       | 324 us: 1.02x slower                                                                   |
| regex_effbot               | 3.42 ms                                                      | 3.48 ms: 1.02x slower                                                                  |
| dulwich_log                | 68.3 ms                                                      | 69.8 ms: 1.02x slower                                                                  |
| create_gc_cycles           | 1.59 ms                                                      | 1.63 ms: 1.02x slower                                                                  |
| pycparser                  | 1.28 sec                                                     | 1.32 sec: 1.03x slower                                                                 |
| pickle                     | 9.77 us                                                      | 10.0 us: 1.03x slower                                                                  |
| unpickle_pure_python       | 236 us                                                       | 243 us: 1.03x slower                                                                   |
| docutils                   | 2.87 sec                                                     | 2.95 sec: 1.03x slower                                                                 |
| chameleon                  | 7.42 ms                                                      | 7.72 ms: 1.04x slower                                                                  |
| meteor_contest             | 130 ms                                                       | 137 ms: 1.05x slower                                                                   |
| xml_etree_process          | 56.1 ms                                                      | 59.1 ms: 1.05x slower                                                                  |
| pathlib                    | 19.1 ms                                                      | 20.2 ms: 1.06x slower                                                                  |
| pidigits                   | 251 ms                                                       | 266 ms: 1.06x slower                                                                   |
| unpickle_list              | 4.47 us                                                      | 4.75 us: 1.06x slower                                                                  |
| xml_etree_iterparse        | 106 ms                                                       | 113 ms: 1.07x slower                                                                   |
| richards                   | 49.9 ms                                                      | 53.6 ms: 1.07x slower                                                                  |
| 2to3                       | 286 ms                                                       | 308 ms: 1.08x slower                                                                   |
| go                         | 166 ms                                                       | 179 ms: 1.08x slower                                                                   |
| xml_etree_generate         | 80.5 ms                                                      | 86.9 ms: 1.08x slower                                                                  |
| pickle_list                | 3.89 us                                                      | 4.23 us: 1.09x slower                                                                  |
| regex_v8                   | 23.7 ms                                                      | 25.8 ms: 1.09x slower                                                                  |
| regex_dna                  | 226 ms                                                       | 247 ms: 1.09x slower                                                                   |
| sqlite_synth               | 2.49 us                                                      | 2.74 us: 1.10x slower                                                                  |
| regex_compile              | 157 ms                                                       | 174 ms: 1.11x slower                                                                   |
| unpickle                   | 13.2 us                                                      | 14.6 us: 1.11x slower                                                                  |
| nqueens                    | 99.2 ms                                                      | 111 ms: 1.12x slower                                                                   |
| pprint_pformat             | 1.63 sec                                                     | 1.82 sec: 1.12x slower                                                                 |
| deepcopy_memo              | 37.3 us                                                      | 42.6 us: 1.14x slower                                                                  |
| pprint_safe_repr           | 780 ms                                                       | 895 ms: 1.15x slower                                                                   |
| async_generators           | 322 ms                                                       | 380 ms: 1.18x slower                                                                   |
| pyflate                    | 453 ms                                                       | 538 ms: 1.19x slower                                                                   |
| coverage                   | 66.6 ms                                                      | 79.2 ms: 1.19x slower                                                                  |
| python_startup             | 10.8 ms                                                      | 12.9 ms: 1.19x slower                                                                  |
| telco                      | 6.91 ms                                                      | 8.23 ms: 1.19x slower                                                                  |
| nbody                      | 95.8 ms                                                      | 115 ms: 1.20x slower                                                                   |
| scimark_fft                | 281 ms                                                       | 342 ms: 1.22x slower                                                                   |
| tomli_loads                | 2.27 sec                                                     | 2.83 sec: 1.24x slower                                                                 |
| mako                       | 11.0 ms                                                      | 14.2 ms: 1.29x slower                                                                  |
| scimark_sparse_mat_mult    | 4.04 ms                                                      | 5.27 ms: 1.31x slower                                                                  |
| deltablue                  | 4.03 ms                                                      | 5.32 ms: 1.32x slower                                                                  |
| float                      | 76.0 ms                                                      | 103 ms: 1.35x slower                                                                   |
| scimark_sor                | 109 ms                                                       | 150 ms: 1.37x slower                                                                   |
| hexiom                     | 6.97 ms                                                      | 9.82 ms: 1.41x slower                                                                  |
| python_startup_no_site     | 7.78 ms                                                      | 11.4 ms: 1.46x slower                                                                  |
| Geometric mean             | (ref)                                                        | 1.01x faster                                                                           |

Benchmark hidden because not significant (3): bench_mp_pool, asyncio_websockets, pickle_dict
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 55.57% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
