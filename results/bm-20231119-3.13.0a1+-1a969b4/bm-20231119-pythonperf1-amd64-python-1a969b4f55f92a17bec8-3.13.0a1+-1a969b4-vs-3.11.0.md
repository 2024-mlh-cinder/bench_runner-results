
# Results vs. 3.11.0

- fork: python
- ref: 1a969b4f55f92a17bec8
- machine: windows-amd64
- commit hash: 1a969b4
- commit date: 2023-11-19
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 209 ms: 1.01x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.92 ms: 1.09x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.54 sec: 1.03x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 86.1 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 265 ms: 1.18x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 451 ms: 1.10x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 339 ms: 1.08x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 283 ms: 1.05x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 362 ms: 1.05x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 759 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 482 ms: 1.04x faster                                                        |
| async_tree_io              | 753 ms                                                      | 724 ms: 1.04x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 53.1 ms: 1.02x faster                                                       |
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 84.3 ms: 1.22x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 80.2 ms: 1.13x faster                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 16.2 ms: 1.19x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.64 ms: 1.40x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 132 us: 1.15x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 185 us: 1.12x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 92.6 ms: 1.02x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 36.8 ms: 1.01x faster                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.3 us: 1.03x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.5 ms: 1.04x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.21 us: 1.05x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.74 us: 1.07x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.91 us: 1.09x slower                                                       |
| pickle               | 6.53 us                                                     | 7.12 us: 1.09x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.5 ms: 1.13x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.45 ms: 1.17x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231119-pythonperf1-amd64-python-1a969b4f55f92a17bec8-3.13.0a1+-1a969b4 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 74.3 us: 4.30x faster                                                       |
| generators                 | 34.0 ms                                                     | 21.3 ms: 1.59x faster                                                       |
| comprehensions             | 15.6 us                                                     | 10.6 us: 1.47x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.64 ms: 1.40x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 465 ms: 1.32x faster                                                        |
| mdp                        | 1.73 sec                                                    | 1.35 sec: 1.28x faster                                                      |
| deltablue                  | 2.63 ms                                                     | 2.09 ms: 1.26x faster                                                       |
| raytrace                   | 211 ms                                                      | 168 ms: 1.25x faster                                                        |
| unpack_sequence            | 47.0 ns                                                     | 37.6 ns: 1.25x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 767 us: 1.22x faster                                                        |
| richards_super             | 37.9 ms                                                     | 31.1 ms: 1.22x faster                                                       |
| logging_silent             | 70.7 ns                                                     | 58.5 ns: 1.21x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 82.8 ms: 1.21x faster                                                       |
| async_tree_none            | 314 ms                                                      | 265 ms: 1.18x faster                                                        |
| mako                       | 7.55 ms                                                     | 6.45 ms: 1.17x faster                                                       |
| sympy_str                  | 184 ms                                                      | 158 ms: 1.16x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 988 us: 1.16x faster                                                        |
| unpickle_pure_python       | 152 us                                                      | 132 us: 1.15x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.56 us: 1.15x faster                                                       |
| hexiom                     | 4.51 ms                                                     | 3.94 ms: 1.14x faster                                                       |
| chaos                      | 46.8 ms                                                     | 41.1 ms: 1.14x faster                                                       |
| regex_compile              | 90.8 ms                                                     | 80.2 ms: 1.13x faster                                                       |
| go                         | 98.8 ms                                                     | 88.0 ms: 1.12x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 185 us: 1.12x faster                                                        |
| nqueens                    | 66.1 ms                                                     | 59.0 ms: 1.12x faster                                                       |
| deepcopy                   | 242 us                                                      | 218 us: 1.11x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 12.3 ms: 1.11x faster                                                       |
| sympy_expand               | 299 ms                                                      | 271 ms: 1.10x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 451 ms: 1.10x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 63.8 ms: 1.09x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 4.92 ms: 1.09x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 44.4 ms: 1.08x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 176 ms: 1.08x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 339 ms: 1.08x faster                                                        |
| dulwich_log                | 44.1 ms                                                     | 40.8 ms: 1.08x faster                                                       |
| richards                   | 30.8 ms                                                     | 28.8 ms: 1.07x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 58.3 ms: 1.07x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.18 us: 1.07x faster                                                       |
| deepcopy_memo              | 25.5 us                                                     | 23.9 us: 1.06x faster                                                       |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.90 sec: 1.06x faster                                                      |
| logging_format             | 7.06 us                                                     | 6.64 us: 1.06x faster                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.44 ms: 1.06x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 283 ms: 1.05x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 42.3 ms: 1.05x faster                                                       |
| async_tree_memoization_tg  | 380 ms                                                      | 362 ms: 1.05x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 33.5 ms: 1.05x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 759 ms: 1.05x faster                                                        |
| deepcopy_reduce            | 2.07 us                                                     | 1.98 us: 1.05x faster                                                       |
| tornado_http               | 89.9 ms                                                     | 86.1 ms: 1.04x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 482 ms: 1.04x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 14.1 ms: 1.04x faster                                                       |
| async_tree_io              | 753 ms                                                      | 724 ms: 1.04x faster                                                        |
| pyflate                    | 305 ms                                                      | 293 ms: 1.04x faster                                                        |
| dask                       | 262 ms                                                      | 253 ms: 1.04x faster                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.03 sec: 1.03x faster                                                      |
| docutils                   | 1.59 sec                                                    | 1.54 sec: 1.03x faster                                                      |
| pprint_safe_repr           | 519 ms                                                      | 506 ms: 1.02x faster                                                        |
| scimark_fft                | 181 ms                                                      | 177 ms: 1.02x faster                                                        |
| float                      | 54.4 ms                                                     | 53.1 ms: 1.02x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 92.6 ms: 1.02x faster                                                       |
| meteor_contest             | 75.0 ms                                                     | 73.5 ms: 1.02x faster                                                       |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| xml_etree_process          | 37.0 ms                                                     | 36.8 ms: 1.01x faster                                                       |
| 2to3                       | 207 ms                                                      | 209 ms: 1.01x slower                                                        |
| xml_etree_iterparse        | 63.0 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.48 ms: 1.01x slower                                                       |
| coverage                   | 43.0 ms                                                     | 43.9 ms: 1.02x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 62.9 ms: 1.03x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.3 us: 1.03x slower                                                       |
| fannkuch                   | 248 ms                                                      | 256 ms: 1.03x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 734 us: 1.04x slower                                                        |
| json_loads                 | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.5 ms: 1.04x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.21 us: 1.05x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.74 us: 1.07x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 82.2 ms: 1.08x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 75.2 ms: 1.08x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.91 us: 1.09x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.12 us: 1.09x slower                                                       |
| pycparser                  | 705 ms                                                      | 773 ms: 1.10x slower                                                        |
| python_startup_no_site     | 15.5 ms                                                     | 17.5 ms: 1.13x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.64 ms: 1.18x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 16.2 ms: 1.19x slower                                                       |
| nbody                      | 69.3 ms                                                     | 84.3 ms: 1.22x slower                                                       |
| async_generators           | 181 ms                                                      | 224 ms: 1.24x slower                                                        |
| mypy2                      | 226 ms                                                      | 286 ms: 1.26x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmark hidden because not significant (4): bench_thread_pool, regex_dna, tomli_loads, json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
