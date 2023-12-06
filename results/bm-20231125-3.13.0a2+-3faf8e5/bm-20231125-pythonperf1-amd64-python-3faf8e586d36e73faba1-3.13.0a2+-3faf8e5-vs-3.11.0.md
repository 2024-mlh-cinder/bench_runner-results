
# Results vs. 3.11.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: windows-amd64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.00x faster \*
- HPT reliability: 99.52%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 227 ms: 1.09x slower                                                        |
| docutils       | 1.59 sec                                                    | 1.64 sec: 1.03x slower                                                      |
| tornado_http   | 89.9 ms                                                     | 93.5 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                                |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 281 ms: 1.12x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 809 ms: 1.02x slower                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 387 ms: 1.02x slower                                                        |
| async_tree_io              | 753 ms                                                      | 779 ms: 1.03x slower                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 516 ms: 1.04x slower                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 543 ms: 1.08x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_none_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 55.0 ms: 1.01x slower                                                       |
| pidigits       | 149 ms                                                      | 155 ms: 1.05x slower                                                        |
| nbody          | 69.3 ms                                                     | 75.8 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 87.7 ms: 1.04x faster                                                       |
| regex_dna      | 121 ms                                                      | 125 ms: 1.03x slower                                                        |
| regex_v8       | 13.7 ms                                                     | 15.5 ms: 1.13x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.90 ms: 1.25x slower                                                       |
| Geometric mean | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 6.43 ms: 1.23x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 194 us: 1.07x faster                                                        |
| unpickle_pure_python | 152 us                                                      | 143 us: 1.07x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 95.5 ms: 1.01x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.68 us: 1.04x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 66.2 ms: 1.05x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.9 us: 1.06x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.88 us: 1.07x slower                                                       |
| xml_etree_process    | 37.0 ms                                                     | 40.3 ms: 1.09x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.55 sec: 1.09x slower                                                      |
| pickle               | 6.53 us                                                     | 7.27 us: 1.11x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.75 us: 1.12x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 59.0 ms: 1.13x slower                                                       |
| json_loads           | 12.9 us                                                     | 15.1 us: 1.17x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.04x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.6 ms: 1.10x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.3 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.14x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.74 ms: 1.03x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 81.4 us: 3.93x faster                                                       |
| generators                 | 34.0 ms                                                     | 23.8 ms: 1.42x faster                                                       |
| comprehensions             | 15.6 us                                                     | 11.3 us: 1.37x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 493 ms: 1.25x faster                                                        |
| json_dumps                 | 7.90 ms                                                     | 6.43 ms: 1.23x faster                                                       |
| raytrace                   | 211 ms                                                      | 175 ms: 1.20x faster                                                        |
| unpack_sequence            | 47.0 ns                                                     | 39.6 ns: 1.19x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 86.7 ms: 1.15x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.51 sec: 1.14x faster                                                      |
| deltablue                  | 2.63 ms                                                     | 2.31 ms: 1.14x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 831 us: 1.13x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.59 us: 1.13x faster                                                       |
| chaos                      | 46.8 ms                                                     | 41.7 ms: 1.12x faster                                                       |
| logging_silent             | 70.7 ns                                                     | 63.3 ns: 1.12x faster                                                       |
| async_tree_none            | 314 ms                                                      | 281 ms: 1.12x faster                                                        |
| sympy_str                  | 184 ms                                                      | 170 ms: 1.08x faster                                                        |
| richards_super             | 37.9 ms                                                     | 35.1 ms: 1.08x faster                                                       |
| go                         | 98.8 ms                                                     | 91.7 ms: 1.08x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 1.07 ms: 1.07x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 194 us: 1.07x faster                                                        |
| unpickle_pure_python       | 152 us                                                      | 143 us: 1.07x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 42.6 ms: 1.05x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 46.2 ms: 1.04x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 13.2 ms: 1.04x faster                                                       |
| nqueens                    | 66.1 ms                                                     | 63.6 ms: 1.04x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.37 us: 1.04x faster                                                       |
| regex_compile              | 90.8 ms                                                     | 87.7 ms: 1.04x faster                                                       |
| hexiom                     | 4.51 ms                                                     | 4.36 ms: 1.04x faster                                                       |
| sympy_expand               | 299 ms                                                      | 289 ms: 1.03x faster                                                        |
| scimark_lu                 | 62.3 ms                                                     | 60.5 ms: 1.03x faster                                                       |
| logging_format             | 7.06 us                                                     | 6.92 us: 1.02x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 190 ms: 1.01x faster                                                        |
| deepcopy                   | 242 us                                                      | 244 us: 1.01x slower                                                        |
| xml_etree_parse            | 94.5 ms                                                     | 95.5 ms: 1.01x slower                                                       |
| float                      | 54.4 ms                                                     | 55.0 ms: 1.01x slower                                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 35.7 ms: 1.02x slower                                                       |
| async_tree_io_tg           | 795 ms                                                      | 809 ms: 1.02x slower                                                        |
| spectral_norm              | 69.9 ms                                                     | 71.2 ms: 1.02x slower                                                       |
| async_tree_memoization_tg  | 380 ms                                                      | 387 ms: 1.02x slower                                                        |
| pyflate                    | 305 ms                                                      | 311 ms: 1.02x slower                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.09 sec: 1.02x slower                                                      |
| mako                       | 7.55 ms                                                     | 7.74 ms: 1.03x slower                                                       |
| meteor_contest             | 75.0 ms                                                     | 77.0 ms: 1.03x slower                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 2.14 us: 1.03x slower                                                       |
| pprint_safe_repr           | 519 ms                                                      | 534 ms: 1.03x slower                                                        |
| dask                       | 262 ms                                                      | 270 ms: 1.03x slower                                                        |
| dulwich_log                | 44.1 ms                                                     | 45.4 ms: 1.03x slower                                                       |
| fannkuch                   | 248 ms                                                      | 256 ms: 1.03x slower                                                        |
| regex_dna                  | 121 ms                                                      | 125 ms: 1.03x slower                                                        |
| docutils                   | 1.59 sec                                                    | 1.64 sec: 1.03x slower                                                      |
| async_tree_io              | 753 ms                                                      | 779 ms: 1.03x slower                                                        |
| tornado_http               | 89.9 ms                                                     | 93.5 ms: 1.04x slower                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 516 ms: 1.04x slower                                                        |
| unpickle_list              | 2.57 us                                                     | 2.68 us: 1.04x slower                                                       |
| coroutines                 | 14.7 ms                                                     | 15.3 ms: 1.04x slower                                                       |
| pidigits                   | 149 ms                                                      | 155 ms: 1.05x slower                                                        |
| xml_etree_iterparse        | 63.0 ms                                                     | 66.2 ms: 1.05x slower                                                       |
| bench_thread_pool          | 847 us                                                      | 898 us: 1.06x slower                                                        |
| gc_traversal               | 1.46 ms                                                     | 1.55 ms: 1.06x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.9 us: 1.06x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.88 us: 1.07x slower                                                       |
| coverage                   | 43.0 ms                                                     | 46.2 ms: 1.08x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 762 us: 1.08x slower                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 543 ms: 1.08x slower                                                        |
| scimark_sor                | 76.4 ms                                                     | 82.9 ms: 1.08x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 66.4 ms: 1.09x slower                                                       |
| xml_etree_process          | 37.0 ms                                                     | 40.3 ms: 1.09x slower                                                       |
| 2to3                       | 207 ms                                                      | 227 ms: 1.09x slower                                                        |
| nbody                      | 69.3 ms                                                     | 75.8 ms: 1.09x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.55 sec: 1.09x slower                                                      |
| python_startup             | 18.8 ms                                                     | 20.6 ms: 1.10x slower                                                       |
| pycparser                  | 705 ms                                                      | 777 ms: 1.10x slower                                                        |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.87 ms: 1.11x slower                                                       |
| scimark_fft                | 181 ms                                                      | 202 ms: 1.11x slower                                                        |
| pickle                     | 6.53 us                                                     | 7.27 us: 1.11x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.75 us: 1.12x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 59.0 ms: 1.13x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 15.5 ms: 1.13x slower                                                       |
| json_loads                 | 12.9 us                                                     | 15.1 us: 1.17x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.3 ms: 1.18x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 82.1 ms: 1.18x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.90 ms: 1.25x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.91 ms: 1.25x slower                                                       |
| mypy2                      | 226 ms                                                      | 305 ms: 1.35x slower                                                        |
| async_generators           | 181 ms                                                      | 252 ms: 1.39x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (7): asyncio_tcp_ssl, async_tree_memoization, richards, chameleon, async_tree_none_tg, deepcopy_memo, json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 99.52% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
