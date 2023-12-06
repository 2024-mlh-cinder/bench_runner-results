
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_stubs
- machine: windows-amd64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.04x faster \*
- HPT reliability: 85.26%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 227 ms: 1.09x slower                                                         |
| chameleon      | 5.35 ms                                                     | 5.02 ms: 1.07x faster                                                        |
| docutils       | 1.59 sec                                                    | 1.62 sec: 1.02x slower                                                       |
| tornado_http   | 89.9 ms                                                     | 92.0 ms: 1.02x slower                                                        |
| Geometric mean | (ref)                                                       | 1.02x slower                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 281 ms: 1.12x faster                                                         |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 471 ms: 1.05x faster                                                         |
| async_tree_memoization     | 367 ms                                                      | 357 ms: 1.03x faster                                                         |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 512 ms: 1.02x slower                                                         |
| Geometric mean             | (ref)                                                       | 1.02x faster                                                                 |

Benchmark hidden because not significant (4): async_tree_memoization_tg, async_tree_none_tg, async_tree_io_tg, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 66.3 ms: 1.04x faster                                                        |
| float          | 54.4 ms                                                     | 52.7 ms: 1.03x faster                                                        |
| pidigits       | 149 ms                                                      | 152 ms: 1.03x slower                                                         |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 83.4 ms: 1.09x faster                                                        |
| regex_dna      | 121 ms                                                      | 122 ms: 1.01x slower                                                         |
| regex_effbot   | 1.52 ms                                                     | 1.71 ms: 1.13x slower                                                        |
| regex_v8       | 13.7 ms                                                     | 21.1 ms: 1.54x slower                                                        |
| Geometric mean | (ref)                                                       | 1.13x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.98 ms: 1.32x faster                                                        |
| unpickle_pure_python | 152 us                                                      | 135 us: 1.13x faster                                                         |
| pickle_pure_python   | 207 us                                                      | 184 us: 1.12x faster                                                         |
| tomli_loads          | 1.42 sec                                                    | 1.33 sec: 1.07x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 36.8 ms: 1.01x faster                                                        |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.5 ms: 1.02x slower                                                        |
| xml_etree_generate   | 52.2 ms                                                     | 55.0 ms: 1.05x slower                                                        |
| unpickle             | 7.82 us                                                     | 8.26 us: 1.06x slower                                                        |
| unpickle_list        | 2.57 us                                                     | 2.74 us: 1.07x slower                                                        |
| pickle               | 6.53 us                                                     | 7.03 us: 1.08x slower                                                        |
| pickle_dict          | 17.8 us                                                     | 19.2 us: 1.08x slower                                                        |
| json_loads           | 12.9 us                                                     | 14.6 us: 1.13x slower                                                        |
| pickle_list          | 2.68 us                                                     | 3.44 us: 1.28x slower                                                        |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                 |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                                        |
| python_startup_no_site | 15.5 ms                                                     | 19.1 ms: 1.23x slower                                                        |
| Geometric mean         | (ref)                                                       | 1.16x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.28 ms: 1.20x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 77.0 us: 4.15x faster                                                        |
| generators                 | 34.0 ms                                                     | 21.3 ms: 1.59x faster                                                        |
| comprehensions             | 15.6 us                                                     | 11.3 us: 1.37x faster                                                        |
| json_dumps                 | 7.90 ms                                                     | 5.98 ms: 1.32x faster                                                        |
| richards_super             | 37.9 ms                                                     | 29.1 ms: 1.30x faster                                                        |
| deltablue                  | 2.63 ms                                                     | 2.03 ms: 1.30x faster                                                        |
| mdp                        | 1.73 sec                                                    | 1.39 sec: 1.24x faster                                                       |
| asyncio_tcp                | 614 ms                                                      | 502 ms: 1.22x faster                                                         |
| raytrace                   | 211 ms                                                      | 173 ms: 1.22x faster                                                         |
| logging_silent             | 70.7 ns                                                     | 58.2 ns: 1.21x faster                                                        |
| sqlglot_parse              | 939 us                                                      | 775 us: 1.21x faster                                                         |
| mako                       | 7.55 ms                                                     | 6.28 ms: 1.20x faster                                                        |
| richards                   | 30.8 ms                                                     | 26.1 ms: 1.18x faster                                                        |
| unpack_sequence            | 47.0 ns                                                     | 40.0 ns: 1.18x faster                                                        |
| sympy_sum                  | 100.0 ms                                                    | 87.3 ms: 1.15x faster                                                        |
| sqlite_synth               | 1.79 us                                                     | 1.57 us: 1.14x faster                                                        |
| sqlglot_transpile          | 1.15 ms                                                     | 1.01 ms: 1.13x faster                                                        |
| unpickle_pure_python       | 152 us                                                      | 135 us: 1.13x faster                                                         |
| pickle_pure_python         | 207 us                                                      | 184 us: 1.12x faster                                                         |
| sympy_str                  | 184 ms                                                      | 164 ms: 1.12x faster                                                         |
| async_tree_none            | 314 ms                                                      | 281 ms: 1.12x faster                                                         |
| deepcopy_memo              | 25.5 us                                                     | 23.0 us: 1.11x faster                                                        |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.83 sec: 1.11x faster                                                       |
| chaos                      | 46.8 ms                                                     | 42.5 ms: 1.10x faster                                                        |
| nqueens                    | 66.1 ms                                                     | 60.4 ms: 1.09x faster                                                        |
| regex_compile              | 90.8 ms                                                     | 83.4 ms: 1.09x faster                                                        |
| sympy_expand               | 299 ms                                                      | 278 ms: 1.08x faster                                                         |
| deepcopy                   | 242 us                                                      | 226 us: 1.07x faster                                                         |
| coroutines                 | 14.7 ms                                                     | 13.7 ms: 1.07x faster                                                        |
| tomli_loads                | 1.42 sec                                                    | 1.33 sec: 1.07x faster                                                       |
| chameleon                  | 5.35 ms                                                     | 5.02 ms: 1.07x faster                                                        |
| scimark_lu                 | 62.3 ms                                                     | 58.6 ms: 1.06x faster                                                        |
| go                         | 98.8 ms                                                     | 93.1 ms: 1.06x faster                                                        |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 471 ms: 1.05x faster                                                         |
| hexiom                     | 4.51 ms                                                     | 4.31 ms: 1.05x faster                                                        |
| sympy_integrate            | 13.7 ms                                                     | 13.1 ms: 1.05x faster                                                        |
| logging_simple             | 6.60 us                                                     | 6.32 us: 1.05x faster                                                        |
| spectral_norm              | 69.9 ms                                                     | 66.9 ms: 1.05x faster                                                        |
| nbody                      | 69.3 ms                                                     | 66.3 ms: 1.04x faster                                                        |
| logging_format             | 7.06 us                                                     | 6.82 us: 1.04x faster                                                        |
| crypto_pyaes               | 48.2 ms                                                     | 46.6 ms: 1.03x faster                                                        |
| deepcopy_reduce            | 2.07 us                                                     | 2.01 us: 1.03x faster                                                        |
| float                      | 54.4 ms                                                     | 52.7 ms: 1.03x faster                                                        |
| sqlglot_normalize          | 191 ms                                                      | 186 ms: 1.03x faster                                                         |
| async_tree_memoization     | 367 ms                                                      | 357 ms: 1.03x faster                                                         |
| pprint_pformat             | 1.06 sec                                                    | 1.04 sec: 1.02x faster                                                       |
| pycparser                  | 705 ms                                                      | 692 ms: 1.02x faster                                                         |
| pprint_safe_repr           | 519 ms                                                      | 513 ms: 1.01x faster                                                         |
| xml_etree_process          | 37.0 ms                                                     | 36.8 ms: 1.01x faster                                                        |
| fannkuch                   | 248 ms                                                      | 250 ms: 1.01x slower                                                         |
| dulwich_log                | 44.1 ms                                                     | 44.3 ms: 1.01x slower                                                        |
| regex_dna                  | 121 ms                                                      | 122 ms: 1.01x slower                                                         |
| sqlglot_optimize           | 35.1 ms                                                     | 35.4 ms: 1.01x slower                                                        |
| scimark_monte_carlo        | 44.6 ms                                                     | 45.1 ms: 1.01x slower                                                        |
| meteor_contest             | 75.0 ms                                                     | 76.1 ms: 1.01x slower                                                        |
| docutils                   | 1.59 sec                                                    | 1.62 sec: 1.02x slower                                                       |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 512 ms: 1.02x slower                                                         |
| tornado_http               | 89.9 ms                                                     | 92.0 ms: 1.02x slower                                                        |
| xml_etree_iterparse        | 63.0 ms                                                     | 64.5 ms: 1.02x slower                                                        |
| pidigits                   | 149 ms                                                      | 152 ms: 1.03x slower                                                         |
| dask                       | 262 ms                                                      | 269 ms: 1.03x slower                                                         |
| bench_thread_pool          | 847 us                                                      | 876 us: 1.03x slower                                                         |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.71 ms: 1.05x slower                                                        |
| xml_etree_generate         | 52.2 ms                                                     | 55.0 ms: 1.05x slower                                                        |
| gc_traversal               | 1.46 ms                                                     | 1.54 ms: 1.06x slower                                                        |
| unpickle                   | 7.82 us                                                     | 8.26 us: 1.06x slower                                                        |
| create_gc_cycles           | 706 us                                                      | 749 us: 1.06x slower                                                         |
| unpickle_list              | 2.57 us                                                     | 2.74 us: 1.07x slower                                                        |
| scimark_fft                | 181 ms                                                      | 194 ms: 1.07x slower                                                         |
| pickle                     | 6.53 us                                                     | 7.03 us: 1.08x slower                                                        |
| scimark_sor                | 76.4 ms                                                     | 82.6 ms: 1.08x slower                                                        |
| pickle_dict                | 17.8 us                                                     | 19.2 us: 1.08x slower                                                        |
| 2to3                       | 207 ms                                                      | 227 ms: 1.09x slower                                                         |
| python_startup             | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                                        |
| bench_mp_pool              | 61.1 ms                                                     | 67.5 ms: 1.11x slower                                                        |
| json_loads                 | 12.9 us                                                     | 14.6 us: 1.13x slower                                                        |
| regex_effbot               | 1.52 ms                                                     | 1.71 ms: 1.13x slower                                                        |
| pathlib                    | 69.4 ms                                                     | 80.6 ms: 1.16x slower                                                        |
| coverage                   | 43.0 ms                                                     | 51.3 ms: 1.19x slower                                                        |
| telco                      | 3.93 ms                                                     | 4.76 ms: 1.21x slower                                                        |
| python_startup_no_site     | 15.5 ms                                                     | 19.1 ms: 1.23x slower                                                        |
| pickle_list                | 2.68 us                                                     | 3.44 us: 1.28x slower                                                        |
| async_generators           | 181 ms                                                      | 241 ms: 1.33x slower                                                         |
| mypy2                      | 226 ms                                                      | 304 ms: 1.34x slower                                                         |
| regex_v8                   | 13.7 ms                                                     | 21.1 ms: 1.54x slower                                                        |
| Geometric mean             | (ref)                                                       | 1.04x faster                                                                 |

Benchmark hidden because not significant (7): async_tree_memoization_tg, pyflate, async_tree_none_tg, async_tree_io_tg, async_tree_io, xml_etree_parse, json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 85.26% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
