
# Results vs. 3.12.0

- fork: python
- ref: v3.11.0
- machine: windows-amd64
- commit hash: deaf509
- commit date: 2022-10-24
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 207 ms: 1.02x faster                                        |
| chameleon      | 4.95 ms                                                     | 5.35 ms: 1.08x slower                                       |
| docutils       | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                      |
| tornado_http   | 87.2 ms                                                     | 89.9 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_cpu_io_mixed    | 477 ms                                                      | 495 ms: 1.04x slower                                        |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 503 ms: 1.04x slower                                        |
| async_tree_io              | 712 ms                                                      | 753 ms: 1.06x slower                                        |
| async_tree_io_tg           | 742 ms                                                      | 795 ms: 1.07x slower                                        |
| async_tree_none_tg         | 277 ms                                                      | 299 ms: 1.08x slower                                        |
| async_tree_none            | 286 ms                                                      | 314 ms: 1.10x slower                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 380 ms: 1.10x slower                                        |
| async_tree_memoization     | 333 ms                                                      | 367 ms: 1.10x slower                                        |
| Geometric mean             | (ref)                                                       | 1.07x slower                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 149 ms: 1.01x faster                                        |
| Geometric mean | (ref)                                                       | 1.00x faster                                                |

Benchmark hidden because not significant (2): float, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.52 ms: 1.04x faster                                       |
| regex_v8       | 13.5 ms                                                     | 13.7 ms: 1.01x slower                                       |
| regex_dna      | 119 ms                                                      | 121 ms: 1.02x slower                                        |
| regex_compile  | 87.2 ms                                                     | 90.8 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.53 us: 1.13x faster                                       |
| unpickle             | 8.44 us                                                     | 7.82 us: 1.08x faster                                       |
| pickle_list          | 2.88 us                                                     | 2.68 us: 1.08x faster                                       |
| xml_etree_generate   | 55.8 ms                                                     | 52.2 ms: 1.07x faster                                       |
| pickle_dict          | 18.9 us                                                     | 17.8 us: 1.07x faster                                       |
| json_loads           | 13.6 us                                                     | 12.9 us: 1.06x faster                                       |
| unpickle_list        | 2.69 us                                                     | 2.57 us: 1.05x faster                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.0 ms: 1.02x faster                                       |
| tomli_loads          | 1.38 sec                                                    | 1.42 sec: 1.03x slower                                      |
| xml_etree_parse      | 90.5 ms                                                     | 94.5 ms: 1.04x slower                                       |
| pickle_pure_python   | 195 us                                                      | 207 us: 1.06x slower                                        |
| unpickle_pure_python | 134 us                                                      | 152 us: 1.13x slower                                        |
| json_dumps           | 5.83 ms                                                     | 7.90 ms: 1.35x slower                                       |
| Geometric mean       | (ref)                                                       | 1.00x slower                                                |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.5 ms: 1.03x faster                                       |
| Geometric mean         | (ref)                                                       | 1.01x faster                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| django_template | 22.8 ms                                                     | 24.0 ms: 1.05x slower                                       |
| mako            | 7.05 ms                                                     | 7.55 ms: 1.07x slower                                       |
| Geometric mean  | (ref)                                                       | 1.06x slower                                                |

All benchmarks:
===============

| Benchmark                  | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_generators           | 230 ms                                                      | 181 ms: 1.27x faster                                        |
| pathlib                    | 79.6 ms                                                     | 69.4 ms: 1.15x faster                                       |
| pickle                     | 7.38 us                                                     | 6.53 us: 1.13x faster                                       |
| bench_mp_pool              | 67.2 ms                                                     | 61.1 ms: 1.10x faster                                       |
| unpickle                   | 8.44 us                                                     | 7.82 us: 1.08x faster                                       |
| pickle_list                | 2.88 us                                                     | 2.68 us: 1.08x faster                                       |
| xml_etree_generate         | 55.8 ms                                                     | 52.2 ms: 1.07x faster                                       |
| pickle_dict                | 18.9 us                                                     | 17.8 us: 1.07x faster                                       |
| json_loads                 | 13.6 us                                                     | 12.9 us: 1.06x faster                                       |
| unpickle_list              | 2.69 us                                                     | 2.57 us: 1.05x faster                                       |
| scimark_sor                | 79.8 ms                                                     | 76.4 ms: 1.04x faster                                       |
| regex_effbot               | 1.58 ms                                                     | 1.52 ms: 1.04x faster                                       |
| telco                      | 4.08 ms                                                     | 3.93 ms: 1.04x faster                                       |
| create_gc_cycles           | 726 us                                                      | 706 us: 1.03x faster                                        |
| python_startup_no_site     | 15.9 ms                                                     | 15.5 ms: 1.03x faster                                       |
| 2to3                       | 213 ms                                                      | 207 ms: 1.02x faster                                        |
| gc_traversal               | 1.49 ms                                                     | 1.46 ms: 1.02x faster                                       |
| xml_etree_process          | 37.6 ms                                                     | 37.0 ms: 1.02x faster                                       |
| docutils                   | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                      |
| pidigits                   | 150 ms                                                      | 149 ms: 1.01x faster                                        |
| sqlalchemy_declarative     | 84.5 ms                                                     | 83.9 ms: 1.01x faster                                       |
| deepcopy_reduce            | 2.08 us                                                     | 2.07 us: 1.00x faster                                       |
| regex_v8                   | 13.5 ms                                                     | 13.7 ms: 1.01x slower                                       |
| regex_dna                  | 119 ms                                                      | 121 ms: 1.02x slower                                        |
| fannkuch                   | 244 ms                                                      | 248 ms: 1.02x slower                                        |
| bench_thread_pool          | 830 us                                                      | 847 us: 1.02x slower                                        |
| pprint_safe_repr           | 508 ms                                                      | 519 ms: 1.02x slower                                        |
| pprint_pformat             | 1.04 sec                                                    | 1.06 sec: 1.03x slower                                      |
| sqlite_synth               | 1.75 us                                                     | 1.79 us: 1.03x slower                                       |
| dask                       | 255 ms                                                      | 262 ms: 1.03x slower                                        |
| tomli_loads                | 1.38 sec                                                    | 1.42 sec: 1.03x slower                                      |
| sqlglot_optimize           | 34.0 ms                                                     | 35.1 ms: 1.03x slower                                       |
| scimark_sparse_mat_mult    | 2.51 ms                                                     | 2.59 ms: 1.03x slower                                       |
| tornado_http               | 87.2 ms                                                     | 89.9 ms: 1.03x slower                                       |
| dulwich_log                | 42.7 ms                                                     | 44.1 ms: 1.03x slower                                       |
| crypto_pyaes               | 46.4 ms                                                     | 48.2 ms: 1.04x slower                                       |
| async_tree_cpu_io_mixed    | 477 ms                                                      | 495 ms: 1.04x slower                                        |
| scimark_monte_carlo        | 43.0 ms                                                     | 44.6 ms: 1.04x slower                                       |
| pyflate                    | 294 ms                                                      | 305 ms: 1.04x slower                                        |
| coroutines                 | 14.1 ms                                                     | 14.7 ms: 1.04x slower                                       |
| meteor_contest             | 72.1 ms                                                     | 75.0 ms: 1.04x slower                                       |
| async_tree_cpu_io_mixed_tg | 483 ms                                                      | 503 ms: 1.04x slower                                        |
| regex_compile              | 87.2 ms                                                     | 90.8 ms: 1.04x slower                                       |
| deepcopy                   | 233 us                                                      | 242 us: 1.04x slower                                        |
| sqlglot_normalize          | 183 ms                                                      | 191 ms: 1.04x slower                                        |
| xml_etree_parse            | 90.5 ms                                                     | 94.5 ms: 1.04x slower                                       |
| pycparser                  | 673 ms                                                      | 705 ms: 1.05x slower                                        |
| logging_format             | 6.72 us                                                     | 7.06 us: 1.05x slower                                       |
| django_template            | 22.8 ms                                                     | 24.0 ms: 1.05x slower                                       |
| sympy_integrate            | 13.0 ms                                                     | 13.7 ms: 1.06x slower                                       |
| async_tree_io              | 712 ms                                                      | 753 ms: 1.06x slower                                        |
| logging_simple             | 6.21 us                                                     | 6.60 us: 1.06x slower                                       |
| pickle_pure_python         | 195 us                                                      | 207 us: 1.06x slower                                        |
| nqueens                    | 61.7 ms                                                     | 66.1 ms: 1.07x slower                                       |
| async_tree_io_tg           | 742 ms                                                      | 795 ms: 1.07x slower                                        |
| mako                       | 7.05 ms                                                     | 7.55 ms: 1.07x slower                                       |
| asyncio_tcp_ssl            | 1.89 sec                                                    | 2.02 sec: 1.07x slower                                      |
| sympy_str                  | 171 ms                                                      | 184 ms: 1.07x slower                                        |
| sympy_expand               | 278 ms                                                      | 299 ms: 1.08x slower                                        |
| coverage                   | 39.8 ms                                                     | 43.0 ms: 1.08x slower                                       |
| async_tree_none_tg         | 277 ms                                                      | 299 ms: 1.08x slower                                        |
| chameleon                  | 4.95 ms                                                     | 5.35 ms: 1.08x slower                                       |
| scimark_lu                 | 57.5 ms                                                     | 62.3 ms: 1.08x slower                                       |
| mypy2                      | 209 ms                                                      | 226 ms: 1.08x slower                                        |
| deepcopy_memo              | 23.4 us                                                     | 25.5 us: 1.09x slower                                       |
| spectral_norm              | 63.9 ms                                                     | 69.9 ms: 1.09x slower                                       |
| raytrace                   | 192 ms                                                      | 211 ms: 1.09x slower                                        |
| async_tree_none            | 286 ms                                                      | 314 ms: 1.10x slower                                        |
| async_tree_memoization_tg  | 345 ms                                                      | 380 ms: 1.10x slower                                        |
| async_tree_memoization     | 333 ms                                                      | 367 ms: 1.10x slower                                        |
| sympy_sum                  | 90.1 ms                                                     | 100.0 ms: 1.11x slower                                      |
| go                         | 89.0 ms                                                     | 98.8 ms: 1.11x slower                                       |
| chaos                      | 42.1 ms                                                     | 46.8 ms: 1.11x slower                                       |
| comprehensions             | 14.0 us                                                     | 15.6 us: 1.11x slower                                       |
| richards                   | 27.6 ms                                                     | 30.8 ms: 1.12x slower                                       |
| hexiom                     | 4.00 ms                                                     | 4.51 ms: 1.13x slower                                       |
| sqlglot_transpile          | 1.02 ms                                                     | 1.15 ms: 1.13x slower                                       |
| unpickle_pure_python       | 134 us                                                      | 152 us: 1.13x slower                                        |
| sqlalchemy_imperative      | 9.20 ms                                                     | 10.5 ms: 1.14x slower                                       |
| logging_silent             | 60.5 ns                                                     | 70.7 ns: 1.17x slower                                       |
| sqlglot_parse              | 802 us                                                      | 939 us: 1.17x slower                                        |
| richards_super             | 31.2 ms                                                     | 37.9 ms: 1.22x slower                                       |
| mdp                        | 1.42 sec                                                    | 1.73 sec: 1.22x slower                                      |
| deltablue                  | 2.12 ms                                                     | 2.63 ms: 1.24x slower                                       |
| unpack_sequence            | 36.9 ns                                                     | 47.0 ns: 1.27x slower                                       |
| asyncio_tcp                | 471 ms                                                      | 614 ms: 1.30x slower                                        |
| json_dumps                 | 5.83 ms                                                     | 7.90 ms: 1.35x slower                                       |
| generators                 | 22.6 ms                                                     | 34.0 ms: 1.50x slower                                       |
| typing_runtime_protocols   | 96.7 us                                                     | 320 us: 3.31x slower                                        |
| Geometric mean             | (ref)                                                       | 1.06x slower                                                |

Benchmark hidden because not significant (7): float, xml_etree_iterparse, python_startup, scimark_fft, aiohttp, nbody, json
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
