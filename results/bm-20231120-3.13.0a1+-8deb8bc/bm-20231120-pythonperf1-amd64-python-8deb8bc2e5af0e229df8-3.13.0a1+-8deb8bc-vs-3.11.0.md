
# Results vs. 3.11.0

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: windows-amd64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.08x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 212 ms: 1.02x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.75 ms: 1.13x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.55 sec: 1.03x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 95.6 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 264 ms: 1.19x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 451 ms: 1.10x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 341 ms: 1.07x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 281 ms: 1.07x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 478 ms: 1.05x faster                                                        |
| async_tree_io              | 753 ms                                                      | 722 ms: 1.04x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 762 ms: 1.04x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 364 ms: 1.04x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 51.5 ms: 1.06x faster                                                       |
| pidigits       | 149 ms                                                      | 146 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 71.3 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 78.7 ms: 1.15x faster                                                       |
| regex_dna      | 121 ms                                                      | 117 ms: 1.03x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.55 ms: 1.02x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 14.6 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.59 ms: 1.41x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 127 us: 1.20x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 177 us: 1.17x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 92.6 ms: 1.02x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 37.4 ms: 1.01x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.3 us: 1.03x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.12 us: 1.04x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.7 ms: 1.05x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.70 us: 1.05x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.85 us: 1.06x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.9 us: 1.07x slower                                                       |
| pickle               | 6.53 us                                                     | 7.18 us: 1.10x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (1): tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.2 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.45 ms: 1.17x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 76.2 us: 4.20x faster                                                       |
| generators                 | 34.0 ms                                                     | 22.3 ms: 1.52x faster                                                       |
| comprehensions             | 15.6 us                                                     | 10.5 us: 1.48x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.59 ms: 1.41x faster                                                       |
| deltablue                  | 2.63 ms                                                     | 2.04 ms: 1.29x faster                                                       |
| raytrace                   | 211 ms                                                      | 166 ms: 1.27x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 56.2 ns: 1.26x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.38 sec: 1.25x faster                                                      |
| sqlglot_parse              | 939 us                                                      | 762 us: 1.23x faster                                                        |
| richards_super             | 37.9 ms                                                     | 31.0 ms: 1.22x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 82.0 ms: 1.22x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 38.5 ns: 1.22x faster                                                       |
| hexiom                     | 4.51 ms                                                     | 3.74 ms: 1.21x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 127 us: 1.20x faster                                                        |
| chaos                      | 46.8 ms                                                     | 39.3 ms: 1.19x faster                                                       |
| async_tree_none            | 314 ms                                                      | 264 ms: 1.19x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 976 us: 1.18x faster                                                        |
| sympy_str                  | 184 ms                                                      | 157 ms: 1.17x faster                                                        |
| mako                       | 7.55 ms                                                     | 6.45 ms: 1.17x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 177 us: 1.17x faster                                                        |
| asyncio_tcp                | 614 ms                                                      | 531 ms: 1.16x faster                                                        |
| regex_compile              | 90.8 ms                                                     | 78.7 ms: 1.15x faster                                                       |
| sqlite_synth               | 1.79 us                                                     | 1.56 us: 1.15x faster                                                       |
| go                         | 98.8 ms                                                     | 86.8 ms: 1.14x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 4.75 ms: 1.13x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 62.4 ms: 1.12x faster                                                       |
| nqueens                    | 66.1 ms                                                     | 59.1 ms: 1.12x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 12.3 ms: 1.12x faster                                                       |
| coroutines                 | 14.7 ms                                                     | 13.1 ms: 1.12x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 43.2 ms: 1.11x faster                                                       |
| sympy_expand               | 299 ms                                                      | 268 ms: 1.11x faster                                                        |
| scimark_lu                 | 62.3 ms                                                     | 56.8 ms: 1.10x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 451 ms: 1.10x faster                                                        |
| deepcopy                   | 242 us                                                      | 222 us: 1.09x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 23.4 us: 1.09x faster                                                       |
| logging_format             | 7.06 us                                                     | 6.51 us: 1.08x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 176 ms: 1.08x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 41.2 ms: 1.08x faster                                                       |
| richards                   | 30.8 ms                                                     | 28.5 ms: 1.08x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.12 us: 1.08x faster                                                       |
| async_tree_memoization     | 367 ms                                                      | 341 ms: 1.07x faster                                                        |
| dulwich_log                | 44.1 ms                                                     | 41.1 ms: 1.07x faster                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.42 ms: 1.07x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 281 ms: 1.07x faster                                                        |
| pyflate                    | 305 ms                                                      | 287 ms: 1.06x faster                                                        |
| deepcopy_reduce            | 2.07 us                                                     | 1.96 us: 1.06x faster                                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 33.2 ms: 1.06x faster                                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.01 sec: 1.06x faster                                                      |
| float                      | 54.4 ms                                                     | 51.5 ms: 1.06x faster                                                       |
| pprint_safe_repr           | 519 ms                                                      | 493 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 478 ms: 1.05x faster                                                        |
| scimark_fft                | 181 ms                                                      | 174 ms: 1.04x faster                                                        |
| async_tree_io              | 753 ms                                                      | 722 ms: 1.04x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 762 ms: 1.04x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 364 ms: 1.04x faster                                                        |
| regex_dna                  | 121 ms                                                      | 117 ms: 1.03x faster                                                        |
| meteor_contest             | 75.0 ms                                                     | 72.9 ms: 1.03x faster                                                       |
| docutils                   | 1.59 sec                                                    | 1.55 sec: 1.03x faster                                                      |
| xml_etree_parse            | 94.5 ms                                                     | 92.6 ms: 1.02x faster                                                       |
| pidigits                   | 149 ms                                                      | 146 ms: 1.01x faster                                                        |
| scimark_sor                | 76.4 ms                                                     | 76.8 ms: 1.01x slower                                                       |
| xml_etree_process          | 37.0 ms                                                     | 37.4 ms: 1.01x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| fannkuch                   | 248 ms                                                      | 252 ms: 1.02x slower                                                        |
| 2to3                       | 207 ms                                                      | 212 ms: 1.02x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.55 ms: 1.02x slower                                                       |
| dask                       | 262 ms                                                      | 269 ms: 1.03x slower                                                        |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                       |
| nbody                      | 69.3 ms                                                     | 71.3 ms: 1.03x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.3 us: 1.03x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 732 us: 1.04x slower                                                        |
| unpickle                   | 7.82 us                                                     | 8.12 us: 1.04x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.7 ms: 1.05x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 64.3 ms: 1.05x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.70 us: 1.05x slower                                                       |
| coverage                   | 43.0 ms                                                     | 45.3 ms: 1.05x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 14.6 ms: 1.06x slower                                                       |
| tornado_http               | 89.9 ms                                                     | 95.6 ms: 1.06x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.85 us: 1.06x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.9 us: 1.07x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.3 ms: 1.08x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.18 us: 1.10x slower                                                       |
| pycparser                  | 705 ms                                                      | 775 ms: 1.10x slower                                                        |
| pathlib                    | 69.4 ms                                                     | 80.2 ms: 1.16x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.56 ms: 1.16x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.2 ms: 1.17x slower                                                       |
| mypy2                      | 226 ms                                                      | 287 ms: 1.27x slower                                                        |
| async_generators           | 181 ms                                                      | 233 ms: 1.29x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (4): json, asyncio_tcp_ssl, tomli_loads, bench_thread_pool
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
