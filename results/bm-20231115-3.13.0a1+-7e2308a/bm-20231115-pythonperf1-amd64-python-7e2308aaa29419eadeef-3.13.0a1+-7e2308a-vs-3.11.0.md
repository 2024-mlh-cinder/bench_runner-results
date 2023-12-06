
# Results vs. 3.11.0

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: windows-amd64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.08x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 209 ms: 1.01x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.81 ms: 1.11x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.55 sec: 1.02x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 86.4 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 266 ms: 1.18x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 455 ms: 1.09x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 341 ms: 1.08x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 755 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 479 ms: 1.05x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 363 ms: 1.05x faster                                                        |
| async_tree_io              | 753 ms                                                      | 723 ms: 1.04x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 51.7 ms: 1.05x faster                                                       |
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 73.4 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 80.1 ms: 1.13x faster                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.0 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.60 ms: 1.41x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 128 us: 1.19x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 182 us: 1.14x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 91.8 ms: 1.03x faster                                                       |
| unpickle             | 7.82 us                                                     | 7.91 us: 1.01x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.1 ms: 1.02x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.1 us: 1.02x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.61 us: 1.02x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.5 ms: 1.04x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| pickle               | 6.53 us                                                     | 6.89 us: 1.06x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.85 us: 1.07x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_process, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.8 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.51 ms: 1.16x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 75.2 us: 4.25x faster                                                       |
| generators                 | 34.0 ms                                                     | 21.0 ms: 1.62x faster                                                       |
| comprehensions             | 15.6 us                                                     | 10.5 us: 1.49x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.60 ms: 1.41x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 459 ms: 1.34x faster                                                        |
| raytrace                   | 211 ms                                                      | 163 ms: 1.29x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 56.1 ns: 1.26x faster                                                       |
| deltablue                  | 2.63 ms                                                     | 2.13 ms: 1.23x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 82.1 ms: 1.22x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 773 us: 1.21x faster                                                        |
| richards_super             | 37.9 ms                                                     | 31.7 ms: 1.20x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 128 us: 1.19x faster                                                        |
| mdp                        | 1.73 sec                                                    | 1.45 sec: 1.19x faster                                                      |
| chaos                      | 46.8 ms                                                     | 39.6 ms: 1.18x faster                                                       |
| async_tree_none            | 314 ms                                                      | 266 ms: 1.18x faster                                                        |
| sympy_str                  | 184 ms                                                      | 157 ms: 1.17x faster                                                        |
| hexiom                     | 4.51 ms                                                     | 3.85 ms: 1.17x faster                                                       |
| mako                       | 7.55 ms                                                     | 6.51 ms: 1.16x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 992 us: 1.16x faster                                                        |
| nqueens                    | 66.1 ms                                                     | 57.2 ms: 1.16x faster                                                       |
| sqlite_synth               | 1.79 us                                                     | 1.57 us: 1.14x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 41.2 ns: 1.14x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 182 us: 1.14x faster                                                        |
| regex_compile              | 90.8 ms                                                     | 80.1 ms: 1.13x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 61.7 ms: 1.13x faster                                                       |
| go                         | 98.8 ms                                                     | 87.3 ms: 1.13x faster                                                       |
| sympy_expand               | 299 ms                                                      | 267 ms: 1.12x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 12.3 ms: 1.12x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 4.81 ms: 1.11x faster                                                       |
| richards                   | 30.8 ms                                                     | 27.8 ms: 1.11x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 43.5 ms: 1.11x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 56.4 ms: 1.10x faster                                                       |
| deepcopy                   | 242 us                                                      | 220 us: 1.10x faster                                                        |
| logging_format             | 7.06 us                                                     | 6.46 us: 1.09x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.04 us: 1.09x faster                                                       |
| coroutines                 | 14.7 ms                                                     | 13.4 ms: 1.09x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 175 ms: 1.09x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 455 ms: 1.09x faster                                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.86 sec: 1.09x faster                                                      |
| async_tree_memoization     | 367 ms                                                      | 341 ms: 1.08x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 23.7 us: 1.07x faster                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 41.8 ms: 1.07x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 280 ms: 1.07x faster                                                        |
| dulwich_log                | 44.1 ms                                                     | 41.4 ms: 1.07x faster                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 1.95 us: 1.06x faster                                                       |
| sqlglot_optimize           | 35.1 ms                                                     | 33.2 ms: 1.06x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 755 ms: 1.05x faster                                                        |
| float                      | 54.4 ms                                                     | 51.7 ms: 1.05x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 479 ms: 1.05x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 363 ms: 1.05x faster                                                        |
| pyflate                    | 305 ms                                                      | 291 ms: 1.05x faster                                                        |
| async_tree_io              | 753 ms                                                      | 723 ms: 1.04x faster                                                        |
| dask                       | 262 ms                                                      | 252 ms: 1.04x faster                                                        |
| tornado_http               | 89.9 ms                                                     | 86.4 ms: 1.04x faster                                                       |
| pprint_safe_repr           | 519 ms                                                      | 502 ms: 1.03x faster                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.03 sec: 1.03x faster                                                      |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.51 ms: 1.03x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 91.8 ms: 1.03x faster                                                       |
| docutils                   | 1.59 sec                                                    | 1.55 sec: 1.02x faster                                                      |
| meteor_contest             | 75.0 ms                                                     | 73.7 ms: 1.02x faster                                                       |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| scimark_fft                | 181 ms                                                      | 180 ms: 1.01x faster                                                        |
| 2to3                       | 207 ms                                                      | 209 ms: 1.01x slower                                                        |
| unpickle                   | 7.82 us                                                     | 7.91 us: 1.01x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 64.1 ms: 1.02x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.1 us: 1.02x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.61 us: 1.02x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.48 ms: 1.02x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 62.7 ms: 1.03x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 727 us: 1.03x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.5 ms: 1.04x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.8 ms: 1.05x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 80.5 ms: 1.05x slower                                                       |
| pickle                     | 6.53 us                                                     | 6.89 us: 1.06x slower                                                       |
| nbody                      | 69.3 ms                                                     | 73.4 ms: 1.06x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.85 us: 1.07x slower                                                       |
| coverage                   | 43.0 ms                                                     | 46.1 ms: 1.07x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 75.5 ms: 1.09x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 15.0 ms: 1.10x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 17.8 ms: 1.15x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.75 ms: 1.21x slower                                                       |
| async_generators           | 181 ms                                                      | 227 ms: 1.26x slower                                                        |
| mypy2                      | 226 ms                                                      | 286 ms: 1.26x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (7): json, bench_thread_pool, regex_dna, xml_etree_process, fannkuch, tomli_loads, pycparser
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
