
# Results vs. 3.11.0

- fork: python
- ref: v3.12.0
- machine: windows-amd64
- commit hash: 0fb18b0
- commit date: 2023-10-02
- overall geometric mean: 1.06x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 213 ms: 1.02x slower                                        |
| chameleon      | 5.35 ms                                                     | 4.95 ms: 1.08x faster                                       |
| docutils       | 1.59 sec                                                    | 1.61 sec: 1.01x slower                                      |
| tornado_http   | 89.9 ms                                                     | 87.2 ms: 1.03x faster                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_memoization     | 367 ms                                                      | 333 ms: 1.10x faster                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 345 ms: 1.10x faster                                        |
| async_tree_none            | 314 ms                                                      | 286 ms: 1.10x faster                                        |
| async_tree_none_tg         | 299 ms                                                      | 277 ms: 1.08x faster                                        |
| async_tree_io_tg           | 795 ms                                                      | 742 ms: 1.07x faster                                        |
| async_tree_io              | 753 ms                                                      | 712 ms: 1.06x faster                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 483 ms: 1.04x faster                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 477 ms: 1.04x faster                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 150 ms: 1.01x slower                                        |
| Geometric mean | (ref)                                                       | 1.00x slower                                                |

Benchmark hidden because not significant (2): nbody, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 87.2 ms: 1.04x faster                                       |
| regex_dna      | 121 ms                                                      | 119 ms: 1.02x faster                                        |
| regex_v8       | 13.7 ms                                                     | 13.5 ms: 1.01x faster                                       |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.83 ms: 1.35x faster                                       |
| unpickle_pure_python | 152 us                                                      | 134 us: 1.13x faster                                        |
| pickle_pure_python   | 207 us                                                      | 195 us: 1.06x faster                                        |
| xml_etree_parse      | 94.5 ms                                                     | 90.5 ms: 1.04x faster                                       |
| tomli_loads          | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                      |
| xml_etree_process    | 37.0 ms                                                     | 37.6 ms: 1.02x slower                                       |
| unpickle_list        | 2.57 us                                                     | 2.69 us: 1.05x slower                                       |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.06x slower                                       |
| pickle_dict          | 17.8 us                                                     | 18.9 us: 1.07x slower                                       |
| xml_etree_generate   | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                       |
| pickle_list          | 2.68 us                                                     | 2.88 us: 1.08x slower                                       |
| unpickle             | 7.82 us                                                     | 8.44 us: 1.08x slower                                       |
| pickle               | 6.53 us                                                     | 7.38 us: 1.13x slower                                       |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 15.9 ms: 1.03x slower                                       |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako            | 7.55 ms                                                     | 7.05 ms: 1.07x faster                                       |
| django_template | 24.0 ms                                                     | 22.8 ms: 1.05x faster                                       |
| Geometric mean  | (ref)                                                       | 1.06x faster                                                |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 96.7 us: 3.31x faster                                       |
| generators                 | 34.0 ms                                                     | 22.6 ms: 1.50x faster                                       |
| json_dumps                 | 7.90 ms                                                     | 5.83 ms: 1.35x faster                                       |
| asyncio_tcp                | 614 ms                                                      | 471 ms: 1.30x faster                                        |
| unpack_sequence            | 47.0 ns                                                     | 36.9 ns: 1.27x faster                                       |
| deltablue                  | 2.63 ms                                                     | 2.12 ms: 1.24x faster                                       |
| mdp                        | 1.73 sec                                                    | 1.42 sec: 1.22x faster                                      |
| richards_super             | 37.9 ms                                                     | 31.2 ms: 1.22x faster                                       |
| sqlglot_parse              | 939 us                                                      | 802 us: 1.17x faster                                        |
| logging_silent             | 70.7 ns                                                     | 60.5 ns: 1.17x faster                                       |
| sqlalchemy_imperative      | 10.5 ms                                                     | 9.20 ms: 1.14x faster                                       |
| unpickle_pure_python       | 152 us                                                      | 134 us: 1.13x faster                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 1.02 ms: 1.13x faster                                       |
| hexiom                     | 4.51 ms                                                     | 4.00 ms: 1.13x faster                                       |
| richards                   | 30.8 ms                                                     | 27.6 ms: 1.12x faster                                       |
| comprehensions             | 15.6 us                                                     | 14.0 us: 1.11x faster                                       |
| chaos                      | 46.8 ms                                                     | 42.1 ms: 1.11x faster                                       |
| go                         | 98.8 ms                                                     | 89.0 ms: 1.11x faster                                       |
| sympy_sum                  | 100.0 ms                                                    | 90.1 ms: 1.11x faster                                       |
| async_tree_memoization     | 367 ms                                                      | 333 ms: 1.10x faster                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 345 ms: 1.10x faster                                        |
| async_tree_none            | 314 ms                                                      | 286 ms: 1.10x faster                                        |
| raytrace                   | 211 ms                                                      | 192 ms: 1.09x faster                                        |
| spectral_norm              | 69.9 ms                                                     | 63.9 ms: 1.09x faster                                       |
| deepcopy_memo              | 25.5 us                                                     | 23.4 us: 1.09x faster                                       |
| mypy2                      | 226 ms                                                      | 209 ms: 1.08x faster                                        |
| scimark_lu                 | 62.3 ms                                                     | 57.5 ms: 1.08x faster                                       |
| chameleon                  | 5.35 ms                                                     | 4.95 ms: 1.08x faster                                       |
| async_tree_none_tg         | 299 ms                                                      | 277 ms: 1.08x faster                                        |
| coverage                   | 43.0 ms                                                     | 39.8 ms: 1.08x faster                                       |
| sympy_expand               | 299 ms                                                      | 278 ms: 1.08x faster                                        |
| sympy_str                  | 184 ms                                                      | 171 ms: 1.07x faster                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.89 sec: 1.07x faster                                      |
| mako                       | 7.55 ms                                                     | 7.05 ms: 1.07x faster                                       |
| async_tree_io_tg           | 795 ms                                                      | 742 ms: 1.07x faster                                        |
| nqueens                    | 66.1 ms                                                     | 61.7 ms: 1.07x faster                                       |
| pickle_pure_python         | 207 us                                                      | 195 us: 1.06x faster                                        |
| logging_simple             | 6.60 us                                                     | 6.21 us: 1.06x faster                                       |
| async_tree_io              | 753 ms                                                      | 712 ms: 1.06x faster                                        |
| sympy_integrate            | 13.7 ms                                                     | 13.0 ms: 1.06x faster                                       |
| django_template            | 24.0 ms                                                     | 22.8 ms: 1.05x faster                                       |
| logging_format             | 7.06 us                                                     | 6.72 us: 1.05x faster                                       |
| pycparser                  | 705 ms                                                      | 673 ms: 1.05x faster                                        |
| xml_etree_parse            | 94.5 ms                                                     | 90.5 ms: 1.04x faster                                       |
| sqlglot_normalize          | 191 ms                                                      | 183 ms: 1.04x faster                                        |
| deepcopy                   | 242 us                                                      | 233 us: 1.04x faster                                        |
| regex_compile              | 90.8 ms                                                     | 87.2 ms: 1.04x faster                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 483 ms: 1.04x faster                                        |
| meteor_contest             | 75.0 ms                                                     | 72.1 ms: 1.04x faster                                       |
| coroutines                 | 14.7 ms                                                     | 14.1 ms: 1.04x faster                                       |
| pyflate                    | 305 ms                                                      | 294 ms: 1.04x faster                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 43.0 ms: 1.04x faster                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 477 ms: 1.04x faster                                        |
| crypto_pyaes               | 48.2 ms                                                     | 46.4 ms: 1.04x faster                                       |
| dulwich_log                | 44.1 ms                                                     | 42.7 ms: 1.03x faster                                       |
| tornado_http               | 89.9 ms                                                     | 87.2 ms: 1.03x faster                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.51 ms: 1.03x faster                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 34.0 ms: 1.03x faster                                       |
| tomli_loads                | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                      |
| dask                       | 262 ms                                                      | 255 ms: 1.03x faster                                        |
| sqlite_synth               | 1.79 us                                                     | 1.75 us: 1.03x faster                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.04 sec: 1.03x faster                                      |
| pprint_safe_repr           | 519 ms                                                      | 508 ms: 1.02x faster                                        |
| bench_thread_pool          | 847 us                                                      | 830 us: 1.02x faster                                        |
| fannkuch                   | 248 ms                                                      | 244 ms: 1.02x faster                                        |
| regex_dna                  | 121 ms                                                      | 119 ms: 1.02x faster                                        |
| regex_v8                   | 13.7 ms                                                     | 13.5 ms: 1.01x faster                                       |
| deepcopy_reduce            | 2.07 us                                                     | 2.08 us: 1.00x slower                                       |
| sqlalchemy_declarative     | 83.9 ms                                                     | 84.5 ms: 1.01x slower                                       |
| pidigits                   | 149 ms                                                      | 150 ms: 1.01x slower                                        |
| docutils                   | 1.59 sec                                                    | 1.61 sec: 1.01x slower                                      |
| xml_etree_process          | 37.0 ms                                                     | 37.6 ms: 1.02x slower                                       |
| gc_traversal               | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                       |
| 2to3                       | 207 ms                                                      | 213 ms: 1.02x slower                                        |
| python_startup_no_site     | 15.5 ms                                                     | 15.9 ms: 1.03x slower                                       |
| create_gc_cycles           | 706 us                                                      | 726 us: 1.03x slower                                        |
| telco                      | 3.93 ms                                                     | 4.08 ms: 1.04x slower                                       |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                       |
| scimark_sor                | 76.4 ms                                                     | 79.8 ms: 1.04x slower                                       |
| unpickle_list              | 2.57 us                                                     | 2.69 us: 1.05x slower                                       |
| json_loads                 | 12.9 us                                                     | 13.6 us: 1.06x slower                                       |
| pickle_dict                | 17.8 us                                                     | 18.9 us: 1.07x slower                                       |
| xml_etree_generate         | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                       |
| pickle_list                | 2.68 us                                                     | 2.88 us: 1.08x slower                                       |
| unpickle                   | 7.82 us                                                     | 8.44 us: 1.08x slower                                       |
| bench_mp_pool              | 61.1 ms                                                     | 67.2 ms: 1.10x slower                                       |
| pickle                     | 6.53 us                                                     | 7.38 us: 1.13x slower                                       |
| pathlib                    | 69.4 ms                                                     | 79.6 ms: 1.15x slower                                       |
| async_generators           | 181 ms                                                      | 230 ms: 1.27x slower                                        |
| Geometric mean             | (ref)                                                       | 1.06x faster                                                |

Benchmark hidden because not significant (7): json, nbody, aiohttp, scimark_fft, python_startup, xml_etree_iterparse, float
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
