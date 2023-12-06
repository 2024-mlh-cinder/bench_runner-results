
# Results vs. 3.11.0

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: windows-amd64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.08x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 209 ms: 1.01x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.80 ms: 1.12x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.54 sec: 1.03x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 87.5 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 266 ms: 1.18x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 447 ms: 1.11x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 339 ms: 1.08x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 357 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 473 ms: 1.06x faster                                                        |
| async_tree_io              | 753 ms                                                      | 714 ms: 1.06x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 755 ms: 1.05x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 52.3 ms: 1.04x faster                                                       |
| pidigits       | 149 ms                                                      | 146 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 74.3 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 79.2 ms: 1.15x faster                                                       |
| regex_dna      | 121 ms                                                      | 121 ms: 1.01x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.59 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.3 ms: 1.12x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.69 ms: 1.39x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 130 us: 1.17x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 179 us: 1.16x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 91.0 ms: 1.04x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 37.2 ms: 1.00x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.2 us: 1.03x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.65 us: 1.03x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.2 ms: 1.04x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.19 us: 1.05x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| pickle               | 6.53 us                                                     | 6.96 us: 1.07x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.86 us: 1.07x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                                |

Benchmark hidden because not significant (2): tomli_loads, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.3 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.46 ms: 1.17x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 75.9 us: 4.22x faster                                                       |
| generators                 | 34.0 ms                                                     | 21.3 ms: 1.60x faster                                                       |
| comprehensions             | 15.6 us                                                     | 10.6 us: 1.47x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.69 ms: 1.39x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 470 ms: 1.31x faster                                                        |
| raytrace                   | 211 ms                                                      | 162 ms: 1.30x faster                                                        |
| mdp                        | 1.73 sec                                                    | 1.35 sec: 1.28x faster                                                      |
| deltablue                  | 2.63 ms                                                     | 2.06 ms: 1.28x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 759 us: 1.24x faster                                                        |
| richards_super             | 37.9 ms                                                     | 30.9 ms: 1.23x faster                                                       |
| logging_silent             | 70.7 ns                                                     | 57.6 ns: 1.23x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 82.8 ms: 1.21x faster                                                       |
| async_tree_none            | 314 ms                                                      | 266 ms: 1.18x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 974 us: 1.18x faster                                                        |
| unpickle_pure_python       | 152 us                                                      | 130 us: 1.17x faster                                                        |
| hexiom                     | 4.51 ms                                                     | 3.85 ms: 1.17x faster                                                       |
| mako                       | 7.55 ms                                                     | 6.46 ms: 1.17x faster                                                       |
| sympy_str                  | 184 ms                                                      | 158 ms: 1.16x faster                                                        |
| pickle_pure_python         | 207 us                                                      | 179 us: 1.16x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.55 us: 1.16x faster                                                       |
| nqueens                    | 66.1 ms                                                     | 57.4 ms: 1.15x faster                                                       |
| chaos                      | 46.8 ms                                                     | 40.6 ms: 1.15x faster                                                       |
| regex_compile              | 90.8 ms                                                     | 79.2 ms: 1.15x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 54.4 ms: 1.15x faster                                                       |
| go                         | 98.8 ms                                                     | 86.5 ms: 1.14x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 12.3 ms: 1.12x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 4.80 ms: 1.12x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 62.8 ms: 1.11x faster                                                       |
| richards                   | 30.8 ms                                                     | 27.7 ms: 1.11x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 447 ms: 1.11x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 40.3 ms: 1.11x faster                                                       |
| sympy_expand               | 299 ms                                                      | 271 ms: 1.10x faster                                                        |
| deepcopy                   | 242 us                                                      | 219 us: 1.10x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 13.3 ms: 1.10x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 175 ms: 1.09x faster                                                        |
| dulwich_log                | 44.1 ms                                                     | 40.5 ms: 1.09x faster                                                       |
| logging_format             | 7.06 us                                                     | 6.48 us: 1.09x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.07 us: 1.09x faster                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.38 ms: 1.09x faster                                                       |
| async_tree_memoization     | 367 ms                                                      | 339 ms: 1.08x faster                                                        |
| crypto_pyaes               | 48.2 ms                                                     | 44.6 ms: 1.08x faster                                                       |
| deepcopy_memo              | 25.5 us                                                     | 23.8 us: 1.07x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 357 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 473 ms: 1.06x faster                                                        |
| deepcopy_reduce            | 2.07 us                                                     | 1.95 us: 1.06x faster                                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 33.2 ms: 1.06x faster                                                       |
| async_tree_io              | 753 ms                                                      | 714 ms: 1.06x faster                                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.92 sec: 1.05x faster                                                      |
| async_tree_io_tg           | 795 ms                                                      | 755 ms: 1.05x faster                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.01 sec: 1.05x faster                                                      |
| pyflate                    | 305 ms                                                      | 291 ms: 1.05x faster                                                        |
| pprint_safe_repr           | 519 ms                                                      | 496 ms: 1.05x faster                                                        |
| scimark_fft                | 181 ms                                                      | 174 ms: 1.04x faster                                                        |
| float                      | 54.4 ms                                                     | 52.3 ms: 1.04x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 91.0 ms: 1.04x faster                                                       |
| docutils                   | 1.59 sec                                                    | 1.54 sec: 1.03x faster                                                      |
| tornado_http               | 89.9 ms                                                     | 87.5 ms: 1.03x faster                                                       |
| bench_thread_pool          | 847 us                                                      | 830 us: 1.02x faster                                                        |
| pidigits                   | 149 ms                                                      | 146 ms: 1.01x faster                                                        |
| meteor_contest             | 75.0 ms                                                     | 74.1 ms: 1.01x faster                                                       |
| fannkuch                   | 248 ms                                                      | 246 ms: 1.01x faster                                                        |
| regex_dna                  | 121 ms                                                      | 121 ms: 1.01x faster                                                        |
| xml_etree_process          | 37.0 ms                                                     | 37.2 ms: 1.00x slower                                                       |
| unpack_sequence            | 47.0 ns                                                     | 47.3 ns: 1.01x slower                                                       |
| 2to3                       | 207 ms                                                      | 209 ms: 1.01x slower                                                        |
| create_gc_cycles           | 706 us                                                      | 718 us: 1.02x slower                                                        |
| bench_mp_pool              | 61.1 ms                                                     | 62.4 ms: 1.02x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.2 us: 1.03x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.65 us: 1.03x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.51 ms: 1.03x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.2 ms: 1.04x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.59 ms: 1.04x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.19 us: 1.05x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 80.7 ms: 1.06x slower                                                       |
| pickle                     | 6.53 us                                                     | 6.96 us: 1.07x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.86 us: 1.07x slower                                                       |
| coverage                   | 43.0 ms                                                     | 46.1 ms: 1.07x slower                                                       |
| nbody                      | 69.3 ms                                                     | 74.3 ms: 1.07x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 15.3 ms: 1.12x slower                                                       |
| pycparser                  | 705 ms                                                      | 802 ms: 1.14x slower                                                        |
| pathlib                    | 69.4 ms                                                     | 79.0 ms: 1.14x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.3 ms: 1.18x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.76 ms: 1.21x slower                                                       |
| async_generators           | 181 ms                                                      | 226 ms: 1.25x slower                                                        |
| mypy2                      | 226 ms                                                      | 286 ms: 1.26x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (3): tomli_loads, xml_etree_iterparse, json
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
