
# Results vs. 3.11.0

- fork: python
- ref: 4ebf2fae9664a4042511
- machine: windows-amd64
- commit hash: 4ebf2fa
- commit date: 2023-10-31
- overall geometric mean: 1.03x faster
- HPT reliability: 59.54%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 222 ms: 1.07x slower                                                        |
| docutils       | 1.59 sec                                                    | 1.65 sec: 1.04x slower                                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmark hidden because not significant (2): chameleon, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 281 ms: 1.11x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 474 ms: 1.04x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 293 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 493 ms: 1.02x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 360 ms: 1.02x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 781 ms: 1.02x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.03x faster                                                                |

Benchmark hidden because not significant (2): async_tree_memoization_tg, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 74.6 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 92.6 ms: 1.02x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.5 ms: 1.13x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.84 ms: 1.35x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 139 us: 1.10x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 200 us: 1.03x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 92.5 ms: 1.02x faster                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.3 ms: 1.02x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.1 us: 1.02x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.17 us: 1.04x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.68 us: 1.04x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.80 us: 1.05x slower                                                       |
| pickle               | 6.53 us                                                     | 6.91 us: 1.06x slower                                                       |
| xml_etree_process    | 37.0 ms                                                     | 39.4 ms: 1.06x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.8 us: 1.07x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 56.4 ms: 1.08x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.55 sec: 1.09x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.0 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.14 ms: 1.06x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 97.6 us: 3.28x faster                                                       |
| generators                 | 34.0 ms                                                     | 22.7 ms: 1.50x faster                                                       |
| comprehensions             | 15.6 us                                                     | 11.2 us: 1.39x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.84 ms: 1.35x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 484 ms: 1.27x faster                                                        |
| mdp                        | 1.73 sec                                                    | 1.42 sec: 1.22x faster                                                      |
| unpack_sequence            | 47.0 ns                                                     | 39.9 ns: 1.18x faster                                                       |
| deltablue                  | 2.63 ms                                                     | 2.23 ms: 1.18x faster                                                       |
| raytrace                   | 211 ms                                                      | 182 ms: 1.16x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.56 us: 1.15x faster                                                       |
| richards_super             | 37.9 ms                                                     | 33.4 ms: 1.13x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 88.3 ms: 1.13x faster                                                       |
| logging_silent             | 70.7 ns                                                     | 62.6 ns: 1.13x faster                                                       |
| async_tree_none            | 314 ms                                                      | 281 ms: 1.11x faster                                                        |
| unpickle_pure_python       | 152 us                                                      | 139 us: 1.10x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 63.7 ms: 1.10x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 861 us: 1.09x faster                                                        |
| sympy_str                  | 184 ms                                                      | 173 ms: 1.07x faster                                                        |
| crypto_pyaes               | 48.2 ms                                                     | 45.3 ms: 1.06x faster                                                       |
| mako                       | 7.55 ms                                                     | 7.14 ms: 1.06x faster                                                       |
| hexiom                     | 4.51 ms                                                     | 4.27 ms: 1.06x faster                                                       |
| nqueens                    | 66.1 ms                                                     | 62.5 ms: 1.06x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 1.09 ms: 1.05x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 13.1 ms: 1.05x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 474 ms: 1.04x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 42.8 ms: 1.04x faster                                                       |
| chaos                      | 46.8 ms                                                     | 45.0 ms: 1.04x faster                                                       |
| mypy2                      | 226 ms                                                      | 218 ms: 1.04x faster                                                        |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.50 ms: 1.04x faster                                                       |
| pickle_pure_python         | 207 us                                                      | 200 us: 1.03x faster                                                        |
| richards                   | 30.8 ms                                                     | 29.8 ms: 1.03x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 60.3 ms: 1.03x faster                                                       |
| xml_etree_parse            | 94.5 ms                                                     | 92.5 ms: 1.02x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 293 ms: 1.02x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 493 ms: 1.02x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 360 ms: 1.02x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 781 ms: 1.02x faster                                                        |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| sympy_expand               | 299 ms                                                      | 296 ms: 1.01x faster                                                        |
| coroutines                 | 14.7 ms                                                     | 14.6 ms: 1.01x faster                                                       |
| go                         | 98.8 ms                                                     | 98.2 ms: 1.01x faster                                                       |
| pyflate                    | 305 ms                                                      | 306 ms: 1.00x slower                                                        |
| fannkuch                   | 248 ms                                                      | 249 ms: 1.01x slower                                                        |
| meteor_contest             | 75.0 ms                                                     | 75.9 ms: 1.01x slower                                                       |
| sqlglot_normalize          | 191 ms                                                      | 194 ms: 1.01x slower                                                        |
| regex_compile              | 90.8 ms                                                     | 92.6 ms: 1.02x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.48 ms: 1.02x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 64.3 ms: 1.02x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.1 us: 1.02x slower                                                       |
| dulwich_log                | 44.1 ms                                                     | 45.2 ms: 1.03x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 62.9 ms: 1.03x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 728 us: 1.03x slower                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 36.3 ms: 1.04x slower                                                       |
| scimark_fft                | 181 ms                                                      | 188 ms: 1.04x slower                                                        |
| docutils                   | 1.59 sec                                                    | 1.65 sec: 1.04x slower                                                      |
| logging_simple             | 6.60 us                                                     | 6.89 us: 1.04x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.17 us: 1.04x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.68 us: 1.04x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.80 us: 1.05x slower                                                       |
| logging_format             | 7.06 us                                                     | 7.38 us: 1.05x slower                                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.12 sec: 1.05x slower                                                      |
| deepcopy                   | 242 us                                                      | 255 us: 1.05x slower                                                        |
| pprint_safe_repr           | 519 ms                                                      | 546 ms: 1.05x slower                                                        |
| coverage                   | 43.0 ms                                                     | 45.5 ms: 1.06x slower                                                       |
| pickle                     | 6.53 us                                                     | 6.91 us: 1.06x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.0 ms: 1.06x slower                                                       |
| regex_effbot               | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                                       |
| xml_etree_process          | 37.0 ms                                                     | 39.4 ms: 1.06x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.8 us: 1.07x slower                                                       |
| 2to3                       | 207 ms                                                      | 222 ms: 1.07x slower                                                        |
| scimark_sor                | 76.4 ms                                                     | 81.9 ms: 1.07x slower                                                       |
| nbody                      | 69.3 ms                                                     | 74.6 ms: 1.08x slower                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 2.24 us: 1.08x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 56.4 ms: 1.08x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.55 sec: 1.09x slower                                                      |
| regex_v8                   | 13.7 ms                                                     | 15.5 ms: 1.13x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 79.7 ms: 1.15x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.0 ms: 1.16x slower                                                       |
| pycparser                  | 705 ms                                                      | 852 ms: 1.21x slower                                                        |
| telco                      | 3.93 ms                                                     | 4.85 ms: 1.23x slower                                                       |
| async_generators           | 181 ms                                                      | 237 ms: 1.31x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.03x faster                                                                |

Benchmark hidden because not significant (10): asyncio_tcp_ssl, bench_thread_pool, async_tree_memoization_tg, deepcopy_memo, regex_dna, tornado_http, float, async_tree_io, chameleon, json
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 59.54% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
