
# Results vs. 3.11.0

- fork: python
- ref: d5491a6eff516ad47906
- machine: windows-amd64
- commit hash: d5491a6
- commit date: 2023-11-13
- overall geometric mean: 1.01x faster \*
- HPT reliability: 54.73%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 223 ms: 1.08x slower                                                        |
| chameleon      | 5.35 ms                                                     | 5.09 ms: 1.05x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.60 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 279 ms: 1.12x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 468 ms: 1.06x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 354 ms: 1.04x faster                                                        |
| async_tree_io              | 753 ms                                                      | 734 ms: 1.03x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 492 ms: 1.02x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 293 ms: 1.02x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 783 ms: 1.02x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (1): async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| float          | 54.4 ms                                                     | 66.0 ms: 1.21x slower                                                       |
| nbody          | 69.3 ms                                                     | 86.6 ms: 1.25x slower                                                       |
| Geometric mean | (ref)                                                       | 1.15x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 118 ms: 1.03x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.56 ms: 1.03x slower                                                       |
| regex_compile  | 90.8 ms                                                     | 95.5 ms: 1.05x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.0 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.73 ms: 1.38x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 182 us: 1.14x faster                                                        |
| unpickle_pure_python | 152 us                                                      | 147 us: 1.03x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 92.8 ms: 1.02x faster                                                       |
| unpickle_list        | 2.57 us                                                     | 2.60 us: 1.01x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.3 us: 1.03x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 55.0 ms: 1.05x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.27 us: 1.06x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.85 us: 1.06x slower                                                       |
| pickle               | 6.53 us                                                     | 7.01 us: 1.07x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 68.7 ms: 1.09x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.75 sec: 1.23x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.1 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 8.56 ms: 1.13x slower                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 79.2 us: 4.04x faster                                                       |
| generators                 | 34.0 ms                                                     | 21.2 ms: 1.60x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.73 ms: 1.38x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 475 ms: 1.29x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 58.8 ns: 1.20x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.45 sec: 1.19x faster                                                      |
| raytrace                   | 211 ms                                                      | 178 ms: 1.18x faster                                                        |
| richards_super             | 37.9 ms                                                     | 32.1 ms: 1.18x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 800 us: 1.17x faster                                                        |
| sympy_sum                  | 100.0 ms                                                    | 85.5 ms: 1.17x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 40.5 ns: 1.16x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 182 us: 1.14x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.58 us: 1.13x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 1.02 ms: 1.13x faster                                                       |
| async_tree_none            | 314 ms                                                      | 279 ms: 1.12x faster                                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.83 sec: 1.11x faster                                                      |
| sympy_str                  | 184 ms                                                      | 167 ms: 1.10x faster                                                        |
| deepcopy                   | 242 us                                                      | 224 us: 1.08x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 65.1 ms: 1.07x faster                                                       |
| richards                   | 30.8 ms                                                     | 28.8 ms: 1.07x faster                                                       |
| coroutines                 | 14.7 ms                                                     | 13.8 ms: 1.07x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 180 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 468 ms: 1.06x faster                                                        |
| deepcopy_reduce            | 2.07 us                                                     | 1.96 us: 1.06x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 5.09 ms: 1.05x faster                                                       |
| sympy_expand               | 299 ms                                                      | 285 ms: 1.05x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 33.7 ms: 1.04x faster                                                       |
| dulwich_log                | 44.1 ms                                                     | 42.5 ms: 1.04x faster                                                       |
| async_tree_memoization     | 367 ms                                                      | 354 ms: 1.04x faster                                                        |
| scimark_lu                 | 62.3 ms                                                     | 60.1 ms: 1.04x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 147 us: 1.03x faster                                                        |
| regex_dna                  | 121 ms                                                      | 118 ms: 1.03x faster                                                        |
| async_tree_io              | 753 ms                                                      | 734 ms: 1.03x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 492 ms: 1.02x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 293 ms: 1.02x faster                                                        |
| chaos                      | 46.8 ms                                                     | 45.9 ms: 1.02x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 92.8 ms: 1.02x faster                                                       |
| deepcopy_memo              | 25.5 us                                                     | 25.0 us: 1.02x faster                                                       |
| async_tree_io_tg           | 795 ms                                                      | 783 ms: 1.02x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 13.5 ms: 1.01x faster                                                       |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| docutils                   | 1.59 sec                                                    | 1.60 sec: 1.01x slower                                                      |
| logging_simple             | 6.60 us                                                     | 6.70 us: 1.01x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.60 us: 1.01x slower                                                       |
| go                         | 98.8 ms                                                     | 101 ms: 1.02x slower                                                        |
| create_gc_cycles           | 706 us                                                      | 722 us: 1.02x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.56 ms: 1.03x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.3 us: 1.03x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 63.4 ms: 1.04x slower                                                       |
| pycparser                  | 705 ms                                                      | 731 ms: 1.04x slower                                                        |
| json_loads                 | 12.9 us                                                     | 13.4 us: 1.04x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.7 ms: 1.05x slower                                                       |
| regex_compile              | 90.8 ms                                                     | 95.5 ms: 1.05x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 55.0 ms: 1.05x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.27 us: 1.06x slower                                                       |
| coverage                   | 43.0 ms                                                     | 45.4 ms: 1.06x slower                                                       |
| comprehensions             | 15.6 us                                                     | 16.5 us: 1.06x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.85 us: 1.06x slower                                                       |
| meteor_contest             | 75.0 ms                                                     | 80.3 ms: 1.07x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.01 us: 1.07x slower                                                       |
| 2to3                       | 207 ms                                                      | 223 ms: 1.08x slower                                                        |
| scimark_sor                | 76.4 ms                                                     | 82.3 ms: 1.08x slower                                                       |
| pprint_safe_repr           | 519 ms                                                      | 562 ms: 1.08x slower                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.15 sec: 1.08x slower                                                      |
| xml_etree_iterparse        | 63.0 ms                                                     | 68.7 ms: 1.09x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 15.0 ms: 1.10x slower                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 52.9 ms: 1.10x slower                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 49.2 ms: 1.10x slower                                                       |
| nqueens                    | 66.1 ms                                                     | 74.2 ms: 1.12x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 78.5 ms: 1.13x slower                                                       |
| mako                       | 7.55 ms                                                     | 8.56 ms: 1.13x slower                                                       |
| pyflate                    | 305 ms                                                      | 347 ms: 1.14x slower                                                        |
| python_startup_no_site     | 15.5 ms                                                     | 18.1 ms: 1.17x slower                                                       |
| deltablue                  | 2.63 ms                                                     | 3.15 ms: 1.20x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.74 ms: 1.21x slower                                                       |
| scimark_fft                | 181 ms                                                      | 220 ms: 1.21x slower                                                        |
| float                      | 54.4 ms                                                     | 66.0 ms: 1.21x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.75 sec: 1.23x slower                                                      |
| nbody                      | 69.3 ms                                                     | 86.6 ms: 1.25x slower                                                       |
| fannkuch                   | 248 ms                                                      | 313 ms: 1.26x slower                                                        |
| mypy2                      | 226 ms                                                      | 293 ms: 1.29x slower                                                        |
| async_generators           | 181 ms                                                      | 237 ms: 1.31x slower                                                        |
| hexiom                     | 4.51 ms                                                     | 6.30 ms: 1.40x slower                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 3.63 ms: 1.40x slower                                                       |
| Geometric mean             | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (6): async_tree_memoization_tg, tornado_http, xml_etree_process, logging_format, json, bench_thread_pool
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 54.73% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
