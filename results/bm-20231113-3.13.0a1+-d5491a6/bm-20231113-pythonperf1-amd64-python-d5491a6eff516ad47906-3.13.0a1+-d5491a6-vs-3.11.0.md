
# Results vs. 3.11.0

- fork: python
- ref: d5491a6eff516ad47906
- machine: windows-amd64
- commit hash: d5491a6
- commit date: 2023-11-13
- overall geometric mean: 1.08x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 210 ms: 1.01x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.82 ms: 1.11x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.54 sec: 1.03x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 86.4 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 265 ms: 1.18x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 449 ms: 1.10x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 340 ms: 1.08x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 279 ms: 1.07x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 474 ms: 1.06x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 360 ms: 1.06x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 761 ms: 1.04x faster                                                        |
| async_tree_io              | 753 ms                                                      | 722 ms: 1.04x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 53.0 ms: 1.03x faster                                                       |
| pidigits       | 149 ms                                                      | 146 ms: 1.02x faster                                                        |
| nbody          | 69.3 ms                                                     | 73.8 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 79.4 ms: 1.14x faster                                                       |
| regex_dna      | 121 ms                                                      | 121 ms: 1.00x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.1 ms: 1.10x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.66 ms: 1.40x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 127 us: 1.20x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 180 us: 1.15x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 90.7 ms: 1.04x faster                                                       |
| unpickle_list        | 2.57 us                                                     | 2.61 us: 1.02x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.45 sec: 1.02x slower                                                      |
| xml_etree_generate   | 52.2 ms                                                     | 54.1 ms: 1.04x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.13 us: 1.04x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.06x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.89 us: 1.08x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 19.4 us: 1.09x slower                                                       |
| pickle               | 6.53 us                                                     | 7.21 us: 1.10x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_iterparse, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 17.9 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.49 ms: 1.16x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 74.5 us: 4.29x faster                                                       |
| generators                 | 34.0 ms                                                     | 20.9 ms: 1.62x faster                                                       |
| comprehensions             | 15.6 us                                                     | 10.8 us: 1.45x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.66 ms: 1.40x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 472 ms: 1.30x faster                                                        |
| deltablue                  | 2.63 ms                                                     | 2.04 ms: 1.29x faster                                                       |
| raytrace                   | 211 ms                                                      | 166 ms: 1.27x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 55.9 ns: 1.26x faster                                                       |
| richards_super             | 37.9 ms                                                     | 30.6 ms: 1.24x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 766 us: 1.23x faster                                                        |
| mdp                        | 1.73 sec                                                    | 1.44 sec: 1.20x faster                                                      |
| unpickle_pure_python       | 152 us                                                      | 127 us: 1.20x faster                                                        |
| sympy_sum                  | 100.0 ms                                                    | 83.5 ms: 1.20x faster                                                       |
| async_tree_none            | 314 ms                                                      | 265 ms: 1.18x faster                                                        |
| hexiom                     | 4.51 ms                                                     | 3.85 ms: 1.17x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 981 us: 1.17x faster                                                        |
| chaos                      | 46.8 ms                                                     | 40.1 ms: 1.17x faster                                                       |
| mako                       | 7.55 ms                                                     | 6.49 ms: 1.16x faster                                                       |
| sympy_str                  | 184 ms                                                      | 159 ms: 1.16x faster                                                        |
| pickle_pure_python         | 207 us                                                      | 180 us: 1.15x faster                                                        |
| go                         | 98.8 ms                                                     | 86.0 ms: 1.15x faster                                                       |
| regex_compile              | 90.8 ms                                                     | 79.4 ms: 1.14x faster                                                       |
| sqlite_synth               | 1.79 us                                                     | 1.58 us: 1.14x faster                                                       |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.79 sec: 1.13x faster                                                      |
| nqueens                    | 66.1 ms                                                     | 58.6 ms: 1.13x faster                                                       |
| spectral_norm              | 69.9 ms                                                     | 62.0 ms: 1.13x faster                                                       |
| richards                   | 30.8 ms                                                     | 27.5 ms: 1.12x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 4.82 ms: 1.11x faster                                                       |
| deepcopy                   | 242 us                                                      | 219 us: 1.11x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 12.4 ms: 1.11x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 449 ms: 1.10x faster                                                        |
| sympy_expand               | 299 ms                                                      | 272 ms: 1.10x faster                                                        |
| scimark_lu                 | 62.3 ms                                                     | 57.1 ms: 1.09x faster                                                       |
| deepcopy_memo              | 25.5 us                                                     | 23.4 us: 1.09x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 44.3 ms: 1.09x faster                                                       |
| dulwich_log                | 44.1 ms                                                     | 40.6 ms: 1.09x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 176 ms: 1.09x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 340 ms: 1.08x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 13.6 ms: 1.08x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 279 ms: 1.07x faster                                                        |
| logging_format             | 7.06 us                                                     | 6.62 us: 1.07x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 44.0 ns: 1.07x faster                                                       |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.43 ms: 1.07x faster                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 1.95 us: 1.07x faster                                                       |
| logging_simple             | 6.60 us                                                     | 6.22 us: 1.06x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 474 ms: 1.06x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 360 ms: 1.06x faster                                                        |
| pprint_pformat             | 1.06 sec                                                    | 1.01 sec: 1.05x faster                                                      |
| pyflate                    | 305 ms                                                      | 291 ms: 1.05x faster                                                        |
| pprint_safe_repr           | 519 ms                                                      | 496 ms: 1.05x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 761 ms: 1.04x faster                                                        |
| async_tree_io              | 753 ms                                                      | 722 ms: 1.04x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 33.6 ms: 1.04x faster                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 42.8 ms: 1.04x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 90.7 ms: 1.04x faster                                                       |
| tornado_http               | 89.9 ms                                                     | 86.4 ms: 1.04x faster                                                       |
| docutils                   | 1.59 sec                                                    | 1.54 sec: 1.03x faster                                                      |
| float                      | 54.4 ms                                                     | 53.0 ms: 1.03x faster                                                       |
| pidigits                   | 149 ms                                                      | 146 ms: 1.02x faster                                                        |
| meteor_contest             | 75.0 ms                                                     | 74.4 ms: 1.01x faster                                                       |
| regex_dna                  | 121 ms                                                      | 121 ms: 1.00x faster                                                        |
| 2to3                       | 207 ms                                                      | 210 ms: 1.01x slower                                                        |
| unpickle_list              | 2.57 us                                                     | 2.61 us: 1.02x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.45 sec: 1.02x slower                                                      |
| bench_mp_pool              | 61.1 ms                                                     | 62.7 ms: 1.03x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 724 us: 1.03x slower                                                        |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.1 ms: 1.04x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.13 us: 1.04x slower                                                       |
| python_startup             | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                                       |
| coverage                   | 43.0 ms                                                     | 45.0 ms: 1.05x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 80.7 ms: 1.06x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.6 us: 1.06x slower                                                       |
| nbody                      | 69.3 ms                                                     | 73.8 ms: 1.07x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.89 us: 1.08x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 19.4 us: 1.09x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 15.1 ms: 1.10x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.21 us: 1.10x slower                                                       |
| pycparser                  | 705 ms                                                      | 784 ms: 1.11x slower                                                        |
| pathlib                    | 69.4 ms                                                     | 78.6 ms: 1.13x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 17.9 ms: 1.15x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.68 ms: 1.19x slower                                                       |
| async_generators           | 181 ms                                                      | 228 ms: 1.26x slower                                                        |
| mypy2                      | 226 ms                                                      | 287 ms: 1.27x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (6): bench_thread_pool, xml_etree_iterparse, xml_etree_process, fannkuch, scimark_fft, json
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
