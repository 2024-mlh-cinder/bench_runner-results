
# Results vs. 3.11.0

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: windows-amd64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.02x faster
- HPT reliability: 79.14%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 222 ms: 1.07x slower                                                        |
| chameleon      | 5.35 ms                                                     | 5.27 ms: 1.02x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.65 sec: 1.04x slower                                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 283 ms: 1.11x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 473 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 494 ms: 1.02x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 295 ms: 1.01x faster                                                        |
| async_tree_io              | 753 ms                                                      | 767 ms: 1.02x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (3): async_tree_memoization, async_tree_io_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 148 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 74.3 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 92.8 ms: 1.02x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.60 ms: 1.05x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.73 ms: 1.38x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 139 us: 1.10x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 200 us: 1.03x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 93.0 ms: 1.02x faster                                                       |
| unpickle_list        | 2.57 us                                                     | 2.64 us: 1.03x slower                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 65.4 ms: 1.04x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.8 us: 1.06x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.06x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.84 us: 1.06x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.31 us: 1.06x slower                                                       |
| pickle               | 6.53 us                                                     | 6.98 us: 1.07x slower                                                       |
| xml_etree_process    | 37.0 ms                                                     | 39.9 ms: 1.08x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 56.7 ms: 1.09x slower                                                       |
| tomli_loads          | 1.42 sec                                                    | 1.56 sec: 1.10x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.6 ms: 1.09x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.1 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 7.09 ms: 1.06x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 101 us: 3.18x faster                                                        |
| generators                 | 34.0 ms                                                     | 23.5 ms: 1.44x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.73 ms: 1.38x faster                                                       |
| comprehensions             | 15.6 us                                                     | 11.3 us: 1.38x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 474 ms: 1.30x faster                                                        |
| unpack_sequence            | 47.0 ns                                                     | 37.8 ns: 1.24x faster                                                       |
| raytrace                   | 211 ms                                                      | 180 ms: 1.17x faster                                                        |
| deltablue                  | 2.63 ms                                                     | 2.25 ms: 1.17x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.49 sec: 1.16x faster                                                      |
| sqlite_synth               | 1.79 us                                                     | 1.56 us: 1.15x faster                                                       |
| sympy_sum                  | 100.0 ms                                                    | 88.1 ms: 1.13x faster                                                       |
| logging_silent             | 70.7 ns                                                     | 62.7 ns: 1.13x faster                                                       |
| richards_super             | 37.9 ms                                                     | 33.8 ms: 1.12x faster                                                       |
| async_tree_none            | 314 ms                                                      | 283 ms: 1.11x faster                                                        |
| unpickle_pure_python       | 152 us                                                      | 139 us: 1.10x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 63.9 ms: 1.09x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 44.2 ms: 1.09x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 862 us: 1.09x faster                                                        |
| chaos                      | 46.8 ms                                                     | 43.3 ms: 1.08x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 58.0 ms: 1.07x faster                                                       |
| mako                       | 7.55 ms                                                     | 7.09 ms: 1.06x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 1.08 ms: 1.06x faster                                                       |
| hexiom                     | 4.51 ms                                                     | 4.28 ms: 1.06x faster                                                       |
| scimark_monte_carlo        | 44.6 ms                                                     | 42.3 ms: 1.05x faster                                                       |
| sympy_str                  | 184 ms                                                      | 175 ms: 1.05x faster                                                        |
| nqueens                    | 66.1 ms                                                     | 63.0 ms: 1.05x faster                                                       |
| sympy_integrate            | 13.7 ms                                                     | 13.1 ms: 1.05x faster                                                       |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 473 ms: 1.05x faster                                                        |
| mypy2                      | 226 ms                                                      | 218 ms: 1.04x faster                                                        |
| pickle_pure_python         | 207 us                                                      | 200 us: 1.03x faster                                                        |
| go                         | 98.8 ms                                                     | 95.9 ms: 1.03x faster                                                       |
| richards                   | 30.8 ms                                                     | 30.3 ms: 1.02x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 494 ms: 1.02x faster                                                        |
| xml_etree_parse            | 94.5 ms                                                     | 93.0 ms: 1.02x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 5.27 ms: 1.02x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 295 ms: 1.01x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 25.2 us: 1.01x faster                                                       |
| pidigits                   | 149 ms                                                      | 148 ms: 1.01x faster                                                        |
| pyflate                    | 305 ms                                                      | 307 ms: 1.01x slower                                                        |
| meteor_contest             | 75.0 ms                                                     | 75.6 ms: 1.01x slower                                                       |
| async_tree_io              | 753 ms                                                      | 767 ms: 1.02x slower                                                        |
| sympy_expand               | 299 ms                                                      | 305 ms: 1.02x slower                                                        |
| regex_compile              | 90.8 ms                                                     | 92.8 ms: 1.02x slower                                                       |
| logging_simple             | 6.60 us                                                     | 6.75 us: 1.02x slower                                                       |
| scimark_fft                | 181 ms                                                      | 186 ms: 1.03x slower                                                        |
| unpickle_list              | 2.57 us                                                     | 2.64 us: 1.03x slower                                                       |
| sqlglot_normalize          | 191 ms                                                      | 197 ms: 1.03x slower                                                        |
| deepcopy                   | 242 us                                                      | 250 us: 1.03x slower                                                        |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                       |
| create_gc_cycles           | 706 us                                                      | 729 us: 1.03x slower                                                        |
| bench_mp_pool              | 61.1 ms                                                     | 63.1 ms: 1.03x slower                                                       |
| pprint_pformat             | 1.06 sec                                                    | 1.10 sec: 1.04x slower                                                      |
| dulwich_log                | 44.1 ms                                                     | 45.6 ms: 1.04x slower                                                       |
| logging_format             | 7.06 us                                                     | 7.31 us: 1.04x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 65.4 ms: 1.04x slower                                                       |
| docutils                   | 1.59 sec                                                    | 1.65 sec: 1.04x slower                                                      |
| pprint_safe_repr           | 519 ms                                                      | 540 ms: 1.04x slower                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 36.7 ms: 1.05x slower                                                       |
| fannkuch                   | 248 ms                                                      | 261 ms: 1.05x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.60 ms: 1.05x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 80.6 ms: 1.06x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.8 us: 1.06x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.6 us: 1.06x slower                                                       |
| pickle_list                | 2.68 us                                                     | 2.84 us: 1.06x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.31 us: 1.06x slower                                                       |
| pickle                     | 6.53 us                                                     | 6.98 us: 1.07x slower                                                       |
| nbody                      | 69.3 ms                                                     | 74.3 ms: 1.07x slower                                                       |
| coverage                   | 43.0 ms                                                     | 46.1 ms: 1.07x slower                                                       |
| 2to3                       | 207 ms                                                      | 222 ms: 1.07x slower                                                        |
| xml_etree_process          | 37.0 ms                                                     | 39.9 ms: 1.08x slower                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 2.25 us: 1.08x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 56.7 ms: 1.09x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.6 ms: 1.09x slower                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.56 sec: 1.10x slower                                                      |
| regex_v8                   | 13.7 ms                                                     | 15.2 ms: 1.11x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 79.6 ms: 1.15x slower                                                       |
| pycparser                  | 705 ms                                                      | 818 ms: 1.16x slower                                                        |
| python_startup_no_site     | 15.5 ms                                                     | 18.1 ms: 1.16x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.79 ms: 1.22x slower                                                       |
| async_generators           | 181 ms                                                      | 238 ms: 1.32x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (11): json, asyncio_tcp_ssl, async_tree_memoization, async_tree_io_tg, bench_thread_pool, regex_dna, float, scimark_sparse_mat_mult, coroutines, tornado_http, async_tree_memoization_tg
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 79.14% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
