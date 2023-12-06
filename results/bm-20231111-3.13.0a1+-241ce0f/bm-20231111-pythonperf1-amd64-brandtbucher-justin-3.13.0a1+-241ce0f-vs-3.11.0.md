
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 241ce0f
- commit date: 2023-11-11
- overall geometric mean: 1.06x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 217 ms: 1.05x slower                                                |
| chameleon      | 5.35 ms                                                     | 4.89 ms: 1.10x faster                                               |
| docutils       | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                              |
| tornado_http   | 89.9 ms                                                     | 88.0 ms: 1.02x faster                                               |
| Geometric mean | (ref)                                                       | 1.02x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 270 ms: 1.16x faster                                                |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 453 ms: 1.09x faster                                                |
| async_tree_memoization     | 367 ms                                                      | 343 ms: 1.07x faster                                                |
| async_tree_none_tg         | 299 ms                                                      | 285 ms: 1.05x faster                                                |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 482 ms: 1.04x faster                                                |
| async_tree_memoization_tg  | 380 ms                                                      | 366 ms: 1.04x faster                                                |
| async_tree_io              | 753 ms                                                      | 730 ms: 1.03x faster                                                |
| async_tree_io_tg           | 795 ms                                                      | 770 ms: 1.03x faster                                                |
| Geometric mean             | (ref)                                                       | 1.06x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 52.8 ms: 1.03x faster                                               |
| pidigits       | 149 ms                                                      | 150 ms: 1.01x slower                                                |
| nbody          | 69.3 ms                                                     | 73.1 ms: 1.06x slower                                               |
| Geometric mean | (ref)                                                       | 1.01x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 82.2 ms: 1.10x faster                                               |
| regex_dna      | 121 ms                                                      | 119 ms: 1.02x faster                                                |
| regex_effbot   | 1.52 ms                                                     | 1.56 ms: 1.03x slower                                               |
| regex_v8       | 13.7 ms                                                     | 14.7 ms: 1.08x slower                                               |
| Geometric mean | (ref)                                                       | 1.00x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.72 ms: 1.38x faster                                               |
| pickle_pure_python   | 207 us                                                      | 183 us: 1.13x faster                                                |
| unpickle_pure_python | 152 us                                                      | 136 us: 1.12x faster                                                |
| tomli_loads          | 1.42 sec                                                    | 1.34 sec: 1.06x faster                                              |
| xml_etree_parse      | 94.5 ms                                                     | 92.8 ms: 1.02x faster                                               |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.8 ms: 1.03x slower                                               |
| pickle_dict          | 17.8 us                                                     | 18.3 us: 1.03x slower                                               |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                               |
| unpickle_list        | 2.57 us                                                     | 2.67 us: 1.04x slower                                               |
| unpickle             | 7.82 us                                                     | 8.15 us: 1.04x slower                                               |
| xml_etree_generate   | 52.2 ms                                                     | 54.6 ms: 1.05x slower                                               |
| pickle_list          | 2.68 us                                                     | 2.88 us: 1.08x slower                                               |
| pickle               | 6.53 us                                                     | 7.22 us: 1.11x slower                                               |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                        |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| python_startup_no_site | 15.5 ms                                                     | 18.9 ms: 1.22x slower                                               |
| Geometric mean         | (ref)                                                       | 1.16x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.59 ms: 1.15x faster                                               |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231111-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-241ce0f |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 76.5 us: 4.18x faster                                               |
| generators                 | 34.0 ms                                                     | 20.7 ms: 1.64x faster                                               |
| json_dumps                 | 7.90 ms                                                     | 5.72 ms: 1.38x faster                                               |
| comprehensions             | 15.6 us                                                     | 11.8 us: 1.32x faster                                               |
| richards_super             | 37.9 ms                                                     | 29.3 ms: 1.29x faster                                               |
| asyncio_tcp                | 614 ms                                                      | 476 ms: 1.29x faster                                                |
| logging_silent             | 70.7 ns                                                     | 55.2 ns: 1.28x faster                                               |
| raytrace                   | 211 ms                                                      | 168 ms: 1.25x faster                                                |
| mdp                        | 1.73 sec                                                    | 1.41 sec: 1.22x faster                                              |
| sqlglot_parse              | 939 us                                                      | 771 us: 1.22x faster                                                |
| deltablue                  | 2.63 ms                                                     | 2.17 ms: 1.21x faster                                               |
| sympy_sum                  | 100.0 ms                                                    | 84.4 ms: 1.18x faster                                               |
| richards                   | 30.8 ms                                                     | 26.2 ms: 1.17x faster                                               |
| async_tree_none            | 314 ms                                                      | 270 ms: 1.16x faster                                                |
| sqlglot_transpile          | 1.15 ms                                                     | 990 us: 1.16x faster                                                |
| sqlite_synth               | 1.79 us                                                     | 1.56 us: 1.15x faster                                               |
| mako                       | 7.55 ms                                                     | 6.59 ms: 1.15x faster                                               |
| sympy_str                  | 184 ms                                                      | 162 ms: 1.14x faster                                                |
| pickle_pure_python         | 207 us                                                      | 183 us: 1.13x faster                                                |
| unpickle_pure_python       | 152 us                                                      | 136 us: 1.12x faster                                                |
| spectral_norm              | 69.9 ms                                                     | 62.6 ms: 1.12x faster                                               |
| chaos                      | 46.8 ms                                                     | 42.3 ms: 1.11x faster                                               |
| regex_compile              | 90.8 ms                                                     | 82.2 ms: 1.10x faster                                               |
| chameleon                  | 5.35 ms                                                     | 4.89 ms: 1.10x faster                                               |
| deepcopy_memo              | 25.5 us                                                     | 23.2 us: 1.10x faster                                               |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 453 ms: 1.09x faster                                                |
| sympy_expand               | 299 ms                                                      | 274 ms: 1.09x faster                                                |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.86 sec: 1.09x faster                                              |
| deepcopy                   | 242 us                                                      | 222 us: 1.09x faster                                                |
| coroutines                 | 14.7 ms                                                     | 13.5 ms: 1.08x faster                                               |
| go                         | 98.8 ms                                                     | 91.3 ms: 1.08x faster                                               |
| sqlglot_normalize          | 191 ms                                                      | 178 ms: 1.08x faster                                                |
| async_tree_memoization     | 367 ms                                                      | 343 ms: 1.07x faster                                                |
| dulwich_log                | 44.1 ms                                                     | 41.3 ms: 1.07x faster                                               |
| logging_format             | 7.06 us                                                     | 6.63 us: 1.06x faster                                               |
| tomli_loads                | 1.42 sec                                                    | 1.34 sec: 1.06x faster                                              |
| sympy_integrate            | 13.7 ms                                                     | 12.9 ms: 1.06x faster                                               |
| logging_simple             | 6.60 us                                                     | 6.23 us: 1.06x faster                                               |
| unpack_sequence            | 47.0 ns                                                     | 44.4 ns: 1.06x faster                                               |
| crypto_pyaes               | 48.2 ms                                                     | 45.6 ms: 1.06x faster                                               |
| scimark_lu                 | 62.3 ms                                                     | 59.2 ms: 1.05x faster                                               |
| async_tree_none_tg         | 299 ms                                                      | 285 ms: 1.05x faster                                                |
| deepcopy_reduce            | 2.07 us                                                     | 1.98 us: 1.05x faster                                               |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 482 ms: 1.04x faster                                                |
| sqlglot_optimize           | 35.1 ms                                                     | 33.7 ms: 1.04x faster                                               |
| pprint_pformat             | 1.06 sec                                                    | 1.02 sec: 1.04x faster                                              |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.49 ms: 1.04x faster                                               |
| async_tree_memoization_tg  | 380 ms                                                      | 366 ms: 1.04x faster                                                |
| async_tree_io              | 753 ms                                                      | 730 ms: 1.03x faster                                                |
| async_tree_io_tg           | 795 ms                                                      | 770 ms: 1.03x faster                                                |
| nqueens                    | 66.1 ms                                                     | 64.1 ms: 1.03x faster                                               |
| float                      | 54.4 ms                                                     | 52.8 ms: 1.03x faster                                               |
| tornado_http               | 89.9 ms                                                     | 88.0 ms: 1.02x faster                                               |
| pprint_safe_repr           | 519 ms                                                      | 508 ms: 1.02x faster                                                |
| xml_etree_parse            | 94.5 ms                                                     | 92.8 ms: 1.02x faster                                               |
| regex_dna                  | 121 ms                                                      | 119 ms: 1.02x faster                                                |
| docutils                   | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                              |
| pyflate                    | 305 ms                                                      | 301 ms: 1.01x faster                                                |
| scimark_monte_carlo        | 44.6 ms                                                     | 44.1 ms: 1.01x faster                                               |
| hexiom                     | 4.51 ms                                                     | 4.56 ms: 1.01x slower                                               |
| pidigits                   | 149 ms                                                      | 150 ms: 1.01x slower                                                |
| meteor_contest             | 75.0 ms                                                     | 76.0 ms: 1.01x slower                                               |
| fannkuch                   | 248 ms                                                      | 253 ms: 1.02x slower                                                |
| regex_effbot               | 1.52 ms                                                     | 1.56 ms: 1.03x slower                                               |
| create_gc_cycles           | 706 us                                                      | 724 us: 1.03x slower                                                |
| xml_etree_iterparse        | 63.0 ms                                                     | 64.8 ms: 1.03x slower                                               |
| pickle_dict                | 17.8 us                                                     | 18.3 us: 1.03x slower                                               |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                               |
| scimark_fft                | 181 ms                                                      | 188 ms: 1.04x slower                                                |
| json_loads                 | 12.9 us                                                     | 13.4 us: 1.04x slower                                               |
| unpickle_list              | 2.57 us                                                     | 2.67 us: 1.04x slower                                               |
| unpickle                   | 7.82 us                                                     | 8.15 us: 1.04x slower                                               |
| xml_etree_generate         | 52.2 ms                                                     | 54.6 ms: 1.05x slower                                               |
| 2to3                       | 207 ms                                                      | 217 ms: 1.05x slower                                                |
| nbody                      | 69.3 ms                                                     | 73.1 ms: 1.06x slower                                               |
| bench_mp_pool              | 61.1 ms                                                     | 64.7 ms: 1.06x slower                                               |
| scimark_sor                | 76.4 ms                                                     | 81.4 ms: 1.06x slower                                               |
| regex_v8                   | 13.7 ms                                                     | 14.7 ms: 1.08x slower                                               |
| pickle_list                | 2.68 us                                                     | 2.88 us: 1.08x slower                                               |
| coverage                   | 43.0 ms                                                     | 46.7 ms: 1.09x slower                                               |
| python_startup             | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| pickle                     | 6.53 us                                                     | 7.22 us: 1.11x slower                                               |
| pathlib                    | 69.4 ms                                                     | 79.0 ms: 1.14x slower                                               |
| telco                      | 3.93 ms                                                     | 4.59 ms: 1.17x slower                                               |
| python_startup_no_site     | 15.5 ms                                                     | 18.9 ms: 1.22x slower                                               |
| mypy2                      | 226 ms                                                      | 292 ms: 1.29x slower                                                |
| async_generators           | 181 ms                                                      | 235 ms: 1.30x slower                                                |
| Geometric mean             | (ref)                                                       | 1.06x faster                                                        |

Benchmark hidden because not significant (4): json, bench_thread_pool, xml_etree_process, pycparser
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
