
# Results vs. 3.11.0

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: windows-amd64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.03x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 231 ms: 1.11x slower                                                        |
| docutils       | 1.59 sec                                                    | 1.72 sec: 1.08x slower                                                      |
| tornado_http   | 89.9 ms                                                     | 94.2 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x slower                                                                |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 287 ms: 1.09x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 386 ms: 1.02x slower                                                        |
| async_tree_io_tg           | 795 ms                                                      | 818 ms: 1.03x slower                                                        |
| async_tree_none_tg         | 299 ms                                                      | 308 ms: 1.03x slower                                                        |
| async_tree_io              | 753 ms                                                      | 778 ms: 1.03x slower                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 523 ms: 1.04x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 151 ms: 1.02x slower                                                        |
| float          | 54.4 ms                                                     | 57.7 ms: 1.06x slower                                                       |
| nbody          | 69.3 ms                                                     | 83.2 ms: 1.20x slower                                                       |
| Geometric mean | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 123 ms: 1.01x slower                                                        |
| regex_compile  | 90.8 ms                                                     | 95.9 ms: 1.06x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.74 ms: 1.15x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 19.4 ms: 1.42x slower                                                       |
| Geometric mean | (ref)                                                       | 1.15x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 6.08 ms: 1.30x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 199 us: 1.04x faster                                                        |
| unpickle_pure_python | 152 us                                                      | 148 us: 1.03x faster                                                        |
| tomli_loads          | 1.42 sec                                                    | 1.50 sec: 1.05x slower                                                      |
| xml_etree_iterparse  | 63.0 ms                                                     | 68.4 ms: 1.09x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 19.3 us: 1.09x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.79 us: 1.09x slower                                                       |
| pickle               | 6.53 us                                                     | 7.12 us: 1.09x slower                                                       |
| xml_etree_process    | 37.0 ms                                                     | 41.3 ms: 1.12x slower                                                       |
| json_loads           | 12.9 us                                                     | 14.5 us: 1.12x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.87 us: 1.13x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 59.6 ms: 1.14x slower                                                       |
| pickle_list          | 2.68 us                                                     | 3.21 us: 1.20x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.3 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.70 ms: 1.02x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231125-pythonperf1-amd64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 85.8 us: 3.73x faster                                                       |
| generators                 | 34.0 ms                                                     | 23.9 ms: 1.42x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 6.08 ms: 1.30x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 498 ms: 1.23x faster                                                        |
| mdp                        | 1.73 sec                                                    | 1.45 sec: 1.19x faster                                                      |
| comprehensions             | 15.6 us                                                     | 13.5 us: 1.16x faster                                                       |
| sqlite_synth               | 1.79 us                                                     | 1.59 us: 1.13x faster                                                       |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.81 sec: 1.12x faster                                                      |
| raytrace                   | 211 ms                                                      | 188 ms: 1.12x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 64.5 ns: 1.10x faster                                                       |
| async_tree_none            | 314 ms                                                      | 287 ms: 1.09x faster                                                        |
| sqlglot_parse              | 939 us                                                      | 867 us: 1.08x faster                                                        |
| sympy_sum                  | 100.0 ms                                                    | 93.5 ms: 1.07x faster                                                       |
| richards_super             | 37.9 ms                                                     | 35.5 ms: 1.07x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 44.4 ns: 1.06x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 199 us: 1.04x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 1.10 ms: 1.04x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 148 us: 1.03x faster                                                        |
| sympy_str                  | 184 ms                                                      | 179 ms: 1.03x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 25.2 us: 1.01x faster                                                       |
| chaos                      | 46.8 ms                                                     | 46.5 ms: 1.01x faster                                                       |
| regex_dna                  | 121 ms                                                      | 123 ms: 1.01x slower                                                        |
| coroutines                 | 14.7 ms                                                     | 14.8 ms: 1.01x slower                                                       |
| go                         | 98.8 ms                                                     | 99.8 ms: 1.01x slower                                                       |
| logging_simple             | 6.60 us                                                     | 6.69 us: 1.01x slower                                                       |
| deepcopy                   | 242 us                                                      | 246 us: 1.02x slower                                                        |
| scimark_lu                 | 62.3 ms                                                     | 63.3 ms: 1.02x slower                                                       |
| richards                   | 30.8 ms                                                     | 31.3 ms: 1.02x slower                                                       |
| pidigits                   | 149 ms                                                      | 151 ms: 1.02x slower                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 386 ms: 1.02x slower                                                        |
| sympy_integrate            | 13.7 ms                                                     | 14.0 ms: 1.02x slower                                                       |
| mako                       | 7.55 ms                                                     | 7.70 ms: 1.02x slower                                                       |
| sympy_expand               | 299 ms                                                      | 305 ms: 1.02x slower                                                        |
| logging_format             | 7.06 us                                                     | 7.26 us: 1.03x slower                                                       |
| async_tree_io_tg           | 795 ms                                                      | 818 ms: 1.03x slower                                                        |
| async_tree_none_tg         | 299 ms                                                      | 308 ms: 1.03x slower                                                        |
| async_tree_io              | 753 ms                                                      | 778 ms: 1.03x slower                                                        |
| nqueens                    | 66.1 ms                                                     | 68.5 ms: 1.04x slower                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 523 ms: 1.04x slower                                                        |
| gc_traversal               | 1.46 ms                                                     | 1.52 ms: 1.04x slower                                                       |
| tornado_http               | 89.9 ms                                                     | 94.2 ms: 1.05x slower                                                       |
| meteor_contest             | 75.0 ms                                                     | 78.7 ms: 1.05x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.50 sec: 1.05x slower                                                      |
| bench_thread_pool          | 847 us                                                      | 893 us: 1.05x slower                                                        |
| pycparser                  | 705 ms                                                      | 744 ms: 1.06x slower                                                        |
| regex_compile              | 90.8 ms                                                     | 95.9 ms: 1.06x slower                                                       |
| sqlglot_normalize          | 191 ms                                                      | 202 ms: 1.06x slower                                                        |
| dulwich_log                | 44.1 ms                                                     | 46.7 ms: 1.06x slower                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 2.20 us: 1.06x slower                                                       |
| dask                       | 262 ms                                                      | 278 ms: 1.06x slower                                                        |
| float                      | 54.4 ms                                                     | 57.7 ms: 1.06x slower                                                       |
| deltablue                  | 2.63 ms                                                     | 2.80 ms: 1.07x slower                                                       |
| coverage                   | 43.0 ms                                                     | 45.9 ms: 1.07x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 754 us: 1.07x slower                                                        |
| pprint_safe_repr           | 519 ms                                                      | 559 ms: 1.08x slower                                                        |
| docutils                   | 1.59 sec                                                    | 1.72 sec: 1.08x slower                                                      |
| bench_mp_pool              | 61.1 ms                                                     | 66.3 ms: 1.08x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 68.4 ms: 1.09x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.5 ms: 1.09x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 19.3 us: 1.09x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.79 us: 1.09x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.12 us: 1.09x slower                                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 38.2 ms: 1.09x slower                                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.16 sec: 1.09x slower                                                      |
| pyflate                    | 305 ms                                                      | 334 ms: 1.10x slower                                                        |
| scimark_sor                | 76.4 ms                                                     | 84.5 ms: 1.11x slower                                                       |
| 2to3                       | 207 ms                                                      | 231 ms: 1.11x slower                                                        |
| xml_etree_process          | 37.0 ms                                                     | 41.3 ms: 1.12x slower                                                       |
| json_loads                 | 12.9 us                                                     | 14.5 us: 1.12x slower                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 50.3 ms: 1.13x slower                                                       |
| hexiom                     | 4.51 ms                                                     | 5.10 ms: 1.13x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.87 us: 1.13x slower                                                       |
| fannkuch                   | 248 ms                                                      | 283 ms: 1.14x slower                                                        |
| xml_etree_generate         | 52.2 ms                                                     | 59.6 ms: 1.14x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.74 ms: 1.15x slower                                                       |
| scimark_fft                | 181 ms                                                      | 212 ms: 1.17x slower                                                        |
| pathlib                    | 69.4 ms                                                     | 81.2 ms: 1.17x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.3 ms: 1.18x slower                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 3.06 ms: 1.18x slower                                                       |
| pickle_list                | 2.68 us                                                     | 3.21 us: 1.20x slower                                                       |
| nbody                      | 69.3 ms                                                     | 83.2 ms: 1.20x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.84 ms: 1.23x slower                                                       |
| spectral_norm              | 69.9 ms                                                     | 86.2 ms: 1.23x slower                                                       |
| mypy2                      | 226 ms                                                      | 313 ms: 1.38x slower                                                        |
| async_generators           | 181 ms                                                      | 251 ms: 1.39x slower                                                        |
| regex_v8                   | 13.7 ms                                                     | 19.4 ms: 1.42x slower                                                       |
| Geometric mean             | (ref)                                                       | 1.03x slower                                                                |

Benchmark hidden because not significant (6): xml_etree_parse, async_tree_cpu_io_mixed, crypto_pyaes, chameleon, async_tree_memoization, json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
