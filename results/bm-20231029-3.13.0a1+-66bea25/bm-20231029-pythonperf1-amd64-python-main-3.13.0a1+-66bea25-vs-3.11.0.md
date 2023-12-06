
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.02x faster
- HPT reliability: 58.05%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 223 ms: 1.08x slower                                        |
| chameleon      | 5.35 ms                                                     | 5.27 ms: 1.02x faster                                       |
| docutils       | 1.59 sec                                                    | 1.63 sec: 1.03x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 283 ms: 1.11x faster                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 477 ms: 1.04x faster                                        |
| async_tree_none_tg         | 299 ms                                                      | 293 ms: 1.02x faster                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 494 ms: 1.02x faster                                        |
| async_tree_io_tg           | 795 ms                                                      | 785 ms: 1.01x faster                                        |
| async_tree_io              | 753 ms                                                      | 763 ms: 1.01x slower                                        |
| Geometric mean             | (ref)                                                       | 1.02x faster                                                |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                        |
| nbody          | 69.3 ms                                                     | 72.9 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                        |
| regex_compile  | 90.8 ms                                                     | 93.3 ms: 1.03x slower                                       |
| regex_effbot   | 1.52 ms                                                     | 1.60 ms: 1.06x slower                                       |
| regex_v8       | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.85 ms: 1.35x faster                                       |
| unpickle_pure_python | 152 us                                                      | 140 us: 1.09x faster                                        |
| pickle_pure_python   | 207 us                                                      | 200 us: 1.04x faster                                        |
| xml_etree_parse      | 94.5 ms                                                     | 92.9 ms: 1.02x faster                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.3 ms: 1.02x slower                                       |
| pickle_dict          | 17.8 us                                                     | 18.5 us: 1.04x slower                                       |
| unpickle             | 7.82 us                                                     | 8.17 us: 1.04x slower                                       |
| unpickle_list        | 2.57 us                                                     | 2.71 us: 1.06x slower                                       |
| pickle_list          | 2.68 us                                                     | 2.84 us: 1.06x slower                                       |
| xml_etree_process    | 37.0 ms                                                     | 39.5 ms: 1.07x slower                                       |
| json_loads           | 12.9 us                                                     | 13.8 us: 1.07x slower                                       |
| xml_etree_generate   | 52.2 ms                                                     | 57.5 ms: 1.10x slower                                       |
| pickle               | 6.53 us                                                     | 7.25 us: 1.11x slower                                       |
| tomli_loads          | 1.42 sec                                                    | 1.59 sec: 1.12x slower                                      |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.9 ms: 1.06x slower                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.0 ms: 1.16x slower                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.17 ms: 1.05x faster                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 97.9 us: 3.27x faster                                       |
| generators                 | 34.0 ms                                                     | 23.1 ms: 1.47x faster                                       |
| json_dumps                 | 7.90 ms                                                     | 5.85 ms: 1.35x faster                                       |
| comprehensions             | 15.6 us                                                     | 11.8 us: 1.32x faster                                       |
| asyncio_tcp                | 614 ms                                                      | 485 ms: 1.27x faster                                        |
| unpack_sequence            | 47.0 ns                                                     | 37.6 ns: 1.25x faster                                       |
| deltablue                  | 2.63 ms                                                     | 2.24 ms: 1.17x faster                                       |
| richards_super             | 37.9 ms                                                     | 32.8 ms: 1.16x faster                                       |
| raytrace                   | 211 ms                                                      | 183 ms: 1.15x faster                                        |
| sqlite_synth               | 1.79 us                                                     | 1.57 us: 1.15x faster                                       |
| mdp                        | 1.73 sec                                                    | 1.51 sec: 1.15x faster                                      |
| sympy_sum                  | 100.0 ms                                                    | 88.5 ms: 1.13x faster                                       |
| logging_silent             | 70.7 ns                                                     | 62.6 ns: 1.13x faster                                       |
| async_tree_none            | 314 ms                                                      | 283 ms: 1.11x faster                                        |
| spectral_norm              | 69.9 ms                                                     | 63.5 ms: 1.10x faster                                       |
| unpickle_pure_python       | 152 us                                                      | 140 us: 1.09x faster                                        |
| sqlglot_parse              | 939 us                                                      | 866 us: 1.08x faster                                        |
| scimark_lu                 | 62.3 ms                                                     | 57.5 ms: 1.08x faster                                       |
| chaos                      | 46.8 ms                                                     | 43.4 ms: 1.08x faster                                       |
| richards                   | 30.8 ms                                                     | 29.0 ms: 1.06x faster                                       |
| sympy_str                  | 184 ms                                                      | 174 ms: 1.06x faster                                        |
| hexiom                     | 4.51 ms                                                     | 4.28 ms: 1.05x faster                                       |
| crypto_pyaes               | 48.2 ms                                                     | 45.7 ms: 1.05x faster                                       |
| mako                       | 7.55 ms                                                     | 7.17 ms: 1.05x faster                                       |
| go                         | 98.8 ms                                                     | 94.1 ms: 1.05x faster                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 1.10 ms: 1.04x faster                                       |
| sympy_integrate            | 13.7 ms                                                     | 13.1 ms: 1.04x faster                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 477 ms: 1.04x faster                                        |
| pickle_pure_python         | 207 us                                                      | 200 us: 1.04x faster                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 43.2 ms: 1.03x faster                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.50 ms: 1.03x faster                                       |
| mypy2                      | 226 ms                                                      | 220 ms: 1.03x faster                                        |
| nqueens                    | 66.1 ms                                                     | 64.3 ms: 1.03x faster                                       |
| async_tree_none_tg         | 299 ms                                                      | 293 ms: 1.02x faster                                        |
| coroutines                 | 14.7 ms                                                     | 14.4 ms: 1.02x faster                                       |
| xml_etree_parse            | 94.5 ms                                                     | 92.9 ms: 1.02x faster                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 494 ms: 1.02x faster                                        |
| chameleon                  | 5.35 ms                                                     | 5.27 ms: 1.02x faster                                       |
| bench_thread_pool          | 847 us                                                      | 835 us: 1.01x faster                                        |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                        |
| async_tree_io_tg           | 795 ms                                                      | 785 ms: 1.01x faster                                        |
| regex_dna                  | 121 ms                                                      | 120 ms: 1.01x faster                                        |
| scimark_fft                | 181 ms                                                      | 180 ms: 1.00x faster                                        |
| meteor_contest             | 75.0 ms                                                     | 75.4 ms: 1.01x slower                                       |
| sqlglot_normalize          | 191 ms                                                      | 193 ms: 1.01x slower                                        |
| async_tree_io              | 753 ms                                                      | 763 ms: 1.01x slower                                        |
| deepcopy_memo              | 25.5 us                                                     | 25.9 us: 1.02x slower                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 64.3 ms: 1.02x slower                                       |
| create_gc_cycles           | 706 us                                                      | 721 us: 1.02x slower                                        |
| fannkuch                   | 248 ms                                                      | 254 ms: 1.02x slower                                        |
| gc_traversal               | 1.46 ms                                                     | 1.49 ms: 1.03x slower                                       |
| docutils                   | 1.59 sec                                                    | 1.63 sec: 1.03x slower                                      |
| regex_compile              | 90.8 ms                                                     | 93.3 ms: 1.03x slower                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.10 sec: 1.03x slower                                      |
| pprint_safe_repr           | 519 ms                                                      | 535 ms: 1.03x slower                                        |
| bench_mp_pool              | 61.1 ms                                                     | 63.2 ms: 1.03x slower                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 36.3 ms: 1.04x slower                                       |
| dulwich_log                | 44.1 ms                                                     | 45.7 ms: 1.04x slower                                       |
| deepcopy                   | 242 us                                                      | 252 us: 1.04x slower                                        |
| pickle_dict                | 17.8 us                                                     | 18.5 us: 1.04x slower                                       |
| logging_format             | 7.06 us                                                     | 7.37 us: 1.04x slower                                       |
| unpickle                   | 7.82 us                                                     | 8.17 us: 1.04x slower                                       |
| logging_simple             | 6.60 us                                                     | 6.90 us: 1.05x slower                                       |
| nbody                      | 69.3 ms                                                     | 72.9 ms: 1.05x slower                                       |
| regex_effbot               | 1.52 ms                                                     | 1.60 ms: 1.06x slower                                       |
| python_startup             | 18.8 ms                                                     | 19.9 ms: 1.06x slower                                       |
| unpickle_list              | 2.57 us                                                     | 2.71 us: 1.06x slower                                       |
| pickle_list                | 2.68 us                                                     | 2.84 us: 1.06x slower                                       |
| scimark_sor                | 76.4 ms                                                     | 81.6 ms: 1.07x slower                                       |
| xml_etree_process          | 37.0 ms                                                     | 39.5 ms: 1.07x slower                                       |
| json_loads                 | 12.9 us                                                     | 13.8 us: 1.07x slower                                       |
| 2to3                       | 207 ms                                                      | 223 ms: 1.08x slower                                        |
| deepcopy_reduce            | 2.07 us                                                     | 2.26 us: 1.09x slower                                       |
| xml_etree_generate         | 52.2 ms                                                     | 57.5 ms: 1.10x slower                                       |
| regex_v8                   | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                       |
| pickle                     | 6.53 us                                                     | 7.25 us: 1.11x slower                                       |
| tomli_loads                | 1.42 sec                                                    | 1.59 sec: 1.12x slower                                      |
| pathlib                    | 69.4 ms                                                     | 80.0 ms: 1.15x slower                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.0 ms: 1.16x slower                                       |
| telco                      | 3.93 ms                                                     | 4.84 ms: 1.23x slower                                       |
| pycparser                  | 705 ms                                                      | 919 ms: 1.30x slower                                        |
| async_generators           | 181 ms                                                      | 246 ms: 1.36x slower                                        |
| Geometric mean             | (ref)                                                       | 1.02x faster                                                |

Benchmark hidden because not significant (8): asyncio_tcp_ssl, async_tree_memoization, json, sympy_expand, pyflate, float, async_tree_memoization_tg, tornado_http
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, coverage, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 58.05% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
