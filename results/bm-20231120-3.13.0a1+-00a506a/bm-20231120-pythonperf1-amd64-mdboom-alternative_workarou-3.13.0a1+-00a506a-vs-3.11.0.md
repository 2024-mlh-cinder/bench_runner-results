
# Results vs. 3.11.0

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 00a506a
- commit date: 2023-11-20
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 212 ms: 1.02x slower                                                        |
| chameleon      | 5.35 ms                                                     | 4.89 ms: 1.10x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 95.4 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 261 ms: 1.20x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 335 ms: 1.09x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 454 ms: 1.09x faster                                                        |
| async_tree_none_tg         | 299 ms                                                      | 277 ms: 1.08x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 356 ms: 1.07x faster                                                        |
| async_tree_io              | 753 ms                                                      | 712 ms: 1.06x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 754 ms: 1.05x faster                                                        |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 482 ms: 1.04x faster                                                        |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 51.3 ms: 1.06x faster                                                       |
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 72.4 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 82.8 ms: 1.10x faster                                                       |
| regex_dna      | 121 ms                                                      | 119 ms: 1.02x faster                                                        |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| regex_v8       | 13.7 ms                                                     | 14.7 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.52 ms: 1.43x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 130 us: 1.17x faster                                                        |
| pickle_pure_python   | 207 us                                                      | 183 us: 1.13x faster                                                        |
| tomli_loads          | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                                      |
| xml_etree_parse      | 94.5 ms                                                     | 92.8 ms: 1.02x faster                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.6 us: 1.04x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.6 ms: 1.05x slower                                                       |
| pickle_list          | 2.68 us                                                     | 2.86 us: 1.07x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.38 us: 1.07x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.75 us: 1.07x slower                                                       |
| pickle               | 6.53 us                                                     | 7.28 us: 1.12x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.8 ms: 1.10x slower                                                       |
| python_startup_no_site | 15.5 ms                                                     | 18.2 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.14x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.61 ms: 1.14x faster                                                       |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 75.1 us: 4.26x faster                                                       |
| generators                 | 34.0 ms                                                     | 21.0 ms: 1.62x faster                                                       |
| comprehensions             | 15.6 us                                                     | 10.2 us: 1.52x faster                                                       |
| json_dumps                 | 7.90 ms                                                     | 5.52 ms: 1.43x faster                                                       |
| deltablue                  | 2.63 ms                                                     | 1.99 ms: 1.32x faster                                                       |
| raytrace                   | 211 ms                                                      | 163 ms: 1.29x faster                                                        |
| logging_silent             | 70.7 ns                                                     | 55.4 ns: 1.28x faster                                                       |
| sqlglot_parse              | 939 us                                                      | 754 us: 1.25x faster                                                        |
| richards_super             | 37.9 ms                                                     | 31.0 ms: 1.22x faster                                                       |
| chaos                      | 46.8 ms                                                     | 38.7 ms: 1.21x faster                                                       |
| mdp                        | 1.73 sec                                                    | 1.43 sec: 1.21x faster                                                      |
| async_tree_none            | 314 ms                                                      | 261 ms: 1.20x faster                                                        |
| sympy_sum                  | 100.0 ms                                                    | 83.4 ms: 1.20x faster                                                       |
| sqlglot_transpile          | 1.15 ms                                                     | 962 us: 1.19x faster                                                        |
| hexiom                     | 4.51 ms                                                     | 3.86 ms: 1.17x faster                                                       |
| unpickle_pure_python       | 152 us                                                      | 130 us: 1.17x faster                                                        |
| go                         | 98.8 ms                                                     | 85.3 ms: 1.16x faster                                                       |
| nqueens                    | 66.1 ms                                                     | 57.3 ms: 1.15x faster                                                       |
| mako                       | 7.55 ms                                                     | 6.61 ms: 1.14x faster                                                       |
| sympy_str                  | 184 ms                                                      | 161 ms: 1.14x faster                                                        |
| pickle_pure_python         | 207 us                                                      | 183 us: 1.13x faster                                                        |
| asyncio_tcp                | 614 ms                                                      | 544 ms: 1.13x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 12.2 ms: 1.13x faster                                                       |
| unpack_sequence            | 47.0 ns                                                     | 41.8 ns: 1.12x faster                                                       |
| deepcopy                   | 242 us                                                      | 216 us: 1.12x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 62.7 ms: 1.12x faster                                                       |
| richards                   | 30.8 ms                                                     | 27.9 ms: 1.10x faster                                                       |
| regex_compile              | 90.8 ms                                                     | 82.8 ms: 1.10x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 4.89 ms: 1.10x faster                                                       |
| sqlglot_normalize          | 191 ms                                                      | 175 ms: 1.09x faster                                                        |
| async_tree_memoization     | 367 ms                                                      | 335 ms: 1.09x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 454 ms: 1.09x faster                                                        |
| logging_simple             | 6.60 us                                                     | 6.07 us: 1.09x faster                                                       |
| crypto_pyaes               | 48.2 ms                                                     | 44.3 ms: 1.09x faster                                                       |
| sympy_expand               | 299 ms                                                      | 276 ms: 1.08x faster                                                        |
| deepcopy_memo              | 25.5 us                                                     | 23.5 us: 1.08x faster                                                       |
| coroutines                 | 14.7 ms                                                     | 13.6 ms: 1.08x faster                                                       |
| deepcopy_reduce            | 2.07 us                                                     | 1.92 us: 1.08x faster                                                       |
| async_tree_none_tg         | 299 ms                                                      | 277 ms: 1.08x faster                                                        |
| logging_format             | 7.06 us                                                     | 6.56 us: 1.08x faster                                                       |
| pprint_pformat             | 1.06 sec                                                    | 993 ms: 1.07x faster                                                        |
| async_tree_memoization_tg  | 380 ms                                                      | 356 ms: 1.07x faster                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 41.8 ms: 1.07x faster                                                       |
| pprint_safe_repr           | 519 ms                                                      | 487 ms: 1.06x faster                                                        |
| sqlglot_optimize           | 35.1 ms                                                     | 32.9 ms: 1.06x faster                                                       |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.90 sec: 1.06x faster                                                      |
| float                      | 54.4 ms                                                     | 51.3 ms: 1.06x faster                                                       |
| async_tree_io              | 753 ms                                                      | 712 ms: 1.06x faster                                                        |
| async_tree_io_tg           | 795 ms                                                      | 754 ms: 1.05x faster                                                        |
| pyflate                    | 305 ms                                                      | 289 ms: 1.05x faster                                                        |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.47 ms: 1.05x faster                                                       |
| sqlite_synth               | 1.79 us                                                     | 1.72 us: 1.05x faster                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 482 ms: 1.04x faster                                                        |
| meteor_contest             | 75.0 ms                                                     | 71.9 ms: 1.04x faster                                                       |
| scimark_lu                 | 62.3 ms                                                     | 60.2 ms: 1.04x faster                                                       |
| tomli_loads                | 1.42 sec                                                    | 1.38 sec: 1.03x faster                                                      |
| regex_dna                  | 121 ms                                                      | 119 ms: 1.02x faster                                                        |
| docutils                   | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                                      |
| xml_etree_parse            | 94.5 ms                                                     | 92.8 ms: 1.02x faster                                                       |
| pidigits                   | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| dulwich_log                | 44.1 ms                                                     | 44.4 ms: 1.01x slower                                                       |
| gc_traversal               | 1.46 ms                                                     | 1.47 ms: 1.01x slower                                                       |
| xml_etree_iterparse        | 63.0 ms                                                     | 63.8 ms: 1.01x slower                                                       |
| fannkuch                   | 248 ms                                                      | 252 ms: 1.02x slower                                                        |
| 2to3                       | 207 ms                                                      | 212 ms: 1.02x slower                                                        |
| dask                       | 262 ms                                                      | 272 ms: 1.04x slower                                                        |
| create_gc_cycles           | 706 us                                                      | 732 us: 1.04x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                                       |
| pickle_dict                | 17.8 us                                                     | 18.6 us: 1.04x slower                                                       |
| nbody                      | 69.3 ms                                                     | 72.4 ms: 1.04x slower                                                       |
| coverage                   | 43.0 ms                                                     | 44.9 ms: 1.05x slower                                                       |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.05x slower                                                       |
| xml_etree_generate         | 52.2 ms                                                     | 54.6 ms: 1.05x slower                                                       |
| scimark_sor                | 76.4 ms                                                     | 80.3 ms: 1.05x slower                                                       |
| bench_mp_pool              | 61.1 ms                                                     | 64.4 ms: 1.05x slower                                                       |
| pycparser                  | 705 ms                                                      | 744 ms: 1.05x slower                                                        |
| tornado_http               | 89.9 ms                                                     | 95.4 ms: 1.06x slower                                                       |
| scimark_fft                | 181 ms                                                      | 192 ms: 1.06x slower                                                        |
| pickle_list                | 2.68 us                                                     | 2.86 us: 1.07x slower                                                       |
| regex_v8                   | 13.7 ms                                                     | 14.7 ms: 1.07x slower                                                       |
| unpickle                   | 7.82 us                                                     | 8.38 us: 1.07x slower                                                       |
| unpickle_list              | 2.57 us                                                     | 2.75 us: 1.07x slower                                                       |
| python_startup             | 18.8 ms                                                     | 20.8 ms: 1.10x slower                                                       |
| pickle                     | 6.53 us                                                     | 7.28 us: 1.12x slower                                                       |
| pathlib                    | 69.4 ms                                                     | 80.6 ms: 1.16x slower                                                       |
| python_startup_no_site     | 15.5 ms                                                     | 18.2 ms: 1.17x slower                                                       |
| telco                      | 3.93 ms                                                     | 4.73 ms: 1.20x slower                                                       |
| async_generators           | 181 ms                                                      | 225 ms: 1.25x slower                                                        |
| mypy2                      | 226 ms                                                      | 287 ms: 1.27x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                                |

Benchmark hidden because not significant (3): bench_thread_pool, xml_etree_process, json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
