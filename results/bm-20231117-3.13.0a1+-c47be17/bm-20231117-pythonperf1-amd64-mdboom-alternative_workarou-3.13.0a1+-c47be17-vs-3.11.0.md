
# Results vs. 3.11.0

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: c47be17
- commit date: 2023-11-17
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 210 ms: 1.01x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.90 ms: 1.09x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.55 sec: 1.02x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 86.9 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 265 ms: 1.18x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 454 ms: 1.09x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 343 ms: 1.07x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 361 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 480 ms: 1.05x faster                                                        |
| async_tree_io              | 753 ms                                                      | 720 ms: 1.05x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 765 ms: 1.04x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 51.5 ms: 1.06x faster                                                       |
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 73.5 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 83.7 ms: 1.08x faster                                                       |
| regex_dna      | 121 ms                                                      | 121 ms: 1.00x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.59 ms: 1.41x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 132 us: 1.15x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 183 us: 1.13x faster                                                        |
| tomli_loads          | 1.42 sec                                                    | 1.37 sec: 1.03x faster                                                      |
| xml_etree_parse      | 94.5 ms                                                     | 93.3 ms: 1.01x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 37.3 ms: 1.01x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 63.7 ms: 1.01x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.61 us: 1.02x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.04 us: 1.03x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.2 ms: 1.04x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.6 us: 1.05x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.89 us: 1.08x slower                                                       |
| pickle               | 6.53 us                                                     | 7.17 us: 1.10x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.8 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.59 ms: 1.15x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 74.1 us: 4.31x faster                                                       |
| generators                 | 34.0 ms                                                     | 21.0 ms: 1.62x faster                                                       |
| comprehensions             | 15.6 us                                                     | 10.3 us: 1.52x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.59 ms: 1.41x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 477 ms: 1.29x faster                                                        |
| deltablue                  | 2.63 ms                                                     | 2.05 ms: 1.28x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 37.6 ns: 1.25x faster                                                       |
| logging_silent             | 70.7 ns                                                     | 57.1 ns: 1.24x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 763 us: 1.23x faster                                                        |
| raytrace                   | 211 ms                                                      | 171 ms: 1.23x faster                                                        |
| sympy_sum                  | 100.0 ms                                                    | 82.8 ms: 1.21x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.44 sec: 1.20x faster                                                      |
| async_tree_none            | 314 ms                                                      | 265 ms: 1.18x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 969 us: 1.18x faster                                                        |
| richards_super             | 37.9 ms                                                     | 32.2 ms: 1.18x faster                                                       |
| chaos                      | 46.8 ms                                                     | 40.2 ms: 1.16x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 60.6 ms: 1.15x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 132 us: 1.15x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.56 us: 1.15x faster                                                       |
| mako                       | 7.55 ms                                                     | 6.59 ms: 1.15x faster                                                       |
| sympy_str                  | 184 ms                                                      | 161 ms: 1.14x faster                                                        |
| hexiom                     | 4.51 ms                                                     | 3.97 ms: 1.14x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 12.1 ms: 1.13x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 183 us: 1.13x faster                                                        |
| go                         | 98.8 ms                                                     | 87.4 ms: 1.13x faster                                                       |
| nqueens                    | 66.1 ms                                                     | 59.3 ms: 1.11x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 43.4 ms: 1.11x faster                                                       |
| deepcopy                   | 242 us                                                      | 219 us: 1.11x faster                                                        |
| sqlglot_normalize          | 191 ms                                                      | 173 ms: 1.10x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 40.5 ms: 1.10x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 4.90 ms: 1.09x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 454 ms: 1.09x faster                                                        |
| logging_simple             | 6.60 us                                                     | 6.07 us: 1.09x faster                                                       |
| regex_compile              | 90.8 ms                                                     | 83.7 ms: 1.08x faster                                                       |
| sympy_expand               | 299 ms                                                      | 276 ms: 1.08x faster                                                        |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.39 ms: 1.08x faster                                                       |
| logging_format             | 7.06 us                                                     | 6.56 us: 1.08x faster                                                       |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.89 sec: 1.07x faster                                                      |
| async_tree_memoization     | 367 ms                                                      | 343 ms: 1.07x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 23.8 us: 1.07x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                                        |
| pprint_pformat             | 1.06 sec                                                    | 997 ms: 1.07x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 32.9 ms: 1.06x faster                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 1.95 us: 1.06x faster                                                       |
| richards                   | 30.8 ms                                                     | 29.0 ms: 1.06x faster                                                       |
| pprint_safe_repr           | 519 ms                                                      | 490 ms: 1.06x faster                                                        |
| pyflate                    | 305 ms                                                      | 288 ms: 1.06x faster                                                        |
| float                      | 54.4 ms                                                     | 51.5 ms: 1.06x faster                                                       |
| async_tree_memoization_tg  | 380 ms                                                      | 361 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 480 ms: 1.05x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 14.0 ms: 1.05x faster                                                       |
| async_tree_io              | 753 ms                                                      | 720 ms: 1.05x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 765 ms: 1.04x faster                                                        |
| tornado_http               | 89.9 ms                                                     | 86.9 ms: 1.03x faster                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.37 sec: 1.03x faster                                                      |
| docutils                   | 1.59 sec                                                    | 1.55 sec: 1.02x faster                                                      |
| dulwich_log                | 44.1 ms                                                     | 43.1 ms: 1.02x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 60.9 ms: 1.02x faster                                                       |
| bench_thread_pool          | 847 us                                                      | 830 us: 1.02x faster                                                        |
| meteor_contest             | 75.0 ms                                                     | 73.5 ms: 1.02x faster                                                       |
| dask                       | 262 ms                                                      | 257 ms: 1.02x faster                                                        |
| xml_etree_parse            | 94.5 ms                                                     | 93.3 ms: 1.01x faster                                                       |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| regex_dna                  | 121 ms                                                      | 121 ms: 1.00x faster                                                        |
| xml_etree_process          | 37.0 ms                                                     | 37.3 ms: 1.01x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 63.7 ms: 1.01x slower                                                       |
| 2to3                       | 207 ms                                                      | 210 ms: 1.01x slower                                                        |
| unpickle_list              | 2.57 us                                                     | 2.61 us: 1.02x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 62.4 ms: 1.02x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.04 us: 1.03x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.2 ms: 1.04x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.7 ms: 1.05x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.6 us: 1.05x slower                                                       |
| fannkuch                   | 248 ms                                                      | 261 ms: 1.05x slower                                                        |
| create_gc_cycles           | 706 us                                                      | 742 us: 1.05x slower                                                        |
| nbody                      | 69.3 ms                                                     | 73.5 ms: 1.06x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 81.4 ms: 1.07x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 74.5 ms: 1.07x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.89 us: 1.08x slower                                                       |
| coverage                   | 43.0 ms                                                     | 46.7 ms: 1.09x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.17 us: 1.10x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                                       |
| pycparser                  | 705 ms                                                      | 795 ms: 1.13x slower                                                        |
| python_startup_no_site     | 15.5 ms                                                     | 17.8 ms: 1.15x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.62 ms: 1.18x slower                                                       |
| async_generators           | 181 ms                                                      | 228 ms: 1.26x slower                                                        |
| mypy2                      | 226 ms                                                      | 287 ms: 1.27x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmark hidden because not significant (2): scimark_fft, json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
