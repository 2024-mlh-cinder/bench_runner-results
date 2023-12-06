
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 218 ms: 1.05x slower                                                |
| chameleon      | 5.35 ms                                                     | 4.89 ms: 1.09x faster                                               |
| docutils       | 1.59 sec                                                    | 1.57 sec: 1.01x faster                                              |
| tornado_http   | 89.9 ms                                                     | 97.5 ms: 1.08x slower                                               |
| Geometric mean | (ref)                                                       | 1.01x slower                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 263 ms: 1.19x faster                                                |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 450 ms: 1.10x faster                                                |
| async_tree_memoization     | 367 ms                                                      | 338 ms: 1.08x faster                                                |
| async_tree_none_tg         | 299 ms                                                      | 281 ms: 1.06x faster                                                |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 479 ms: 1.05x faster                                                |
| async_tree_io              | 753 ms                                                      | 721 ms: 1.04x faster                                                |
| async_tree_memoization_tg  | 380 ms                                                      | 364 ms: 1.04x faster                                                |
| async_tree_io_tg           | 795 ms                                                      | 767 ms: 1.04x faster                                                |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 64.6 ms: 1.07x faster                                               |
| float          | 54.4 ms                                                     | 51.3 ms: 1.06x faster                                               |
| pidigits       | 149 ms                                                      | 150 ms: 1.01x slower                                                |
| Geometric mean | (ref)                                                       | 1.04x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 81.1 ms: 1.12x faster                                               |
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                                |
| regex_effbot   | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                               |
| regex_v8       | 13.7 ms                                                     | 17.9 ms: 1.30x slower                                               |
| Geometric mean | (ref)                                                       | 1.05x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.64 ms: 1.40x faster                                               |
| unpickle_pure_python | 152 us                                                      | 132 us: 1.16x faster                                                |
| pickle_pure_python   | 207 us                                                      | 184 us: 1.13x faster                                                |
| tomli_loads          | 1.42 sec                                                    | 1.28 sec: 1.11x faster                                              |
| xml_etree_parse      | 94.5 ms                                                     | 91.6 ms: 1.03x faster                                               |
| xml_etree_iterparse  | 63.0 ms                                                     | 61.5 ms: 1.02x faster                                               |
| xml_etree_process    | 37.0 ms                                                     | 36.8 ms: 1.01x faster                                               |
| pickle_dict          | 17.8 us                                                     | 18.1 us: 1.02x slower                                               |
| unpickle_list        | 2.57 us                                                     | 2.65 us: 1.03x slower                                               |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                               |
| xml_etree_generate   | 52.2 ms                                                     | 54.5 ms: 1.04x slower                                               |
| unpickle             | 7.82 us                                                     | 8.17 us: 1.04x slower                                               |
| pickle               | 6.53 us                                                     | 6.86 us: 1.05x slower                                               |
| pickle_list          | 2.68 us                                                     | 3.19 us: 1.19x slower                                               |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| python_startup_no_site | 15.5 ms                                                     | 18.7 ms: 1.20x slower                                               |
| Geometric mean         | (ref)                                                       | 1.15x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.19 ms: 1.22x faster                                               |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 74.3 us: 4.31x faster                                               |
| generators                 | 34.0 ms                                                     | 20.6 ms: 1.65x faster                                               |
| json_dumps                 | 7.90 ms                                                     | 5.64 ms: 1.40x faster                                               |
| comprehensions             | 15.6 us                                                     | 11.2 us: 1.39x faster                                               |
| deltablue                  | 2.63 ms                                                     | 2.01 ms: 1.31x faster                                               |
| logging_silent             | 70.7 ns                                                     | 56.6 ns: 1.25x faster                                               |
| richards_super             | 37.9 ms                                                     | 30.4 ms: 1.25x faster                                               |
| mdp                        | 1.73 sec                                                    | 1.38 sec: 1.25x faster                                              |
| sqlglot_parse              | 939 us                                                      | 768 us: 1.22x faster                                                |
| raytrace                   | 211 ms                                                      | 173 ms: 1.22x faster                                                |
| mako                       | 7.55 ms                                                     | 6.19 ms: 1.22x faster                                               |
| spectral_norm              | 69.9 ms                                                     | 58.6 ms: 1.19x faster                                               |
| async_tree_none            | 314 ms                                                      | 263 ms: 1.19x faster                                                |
| sympy_sum                  | 100.0 ms                                                    | 84.6 ms: 1.18x faster                                               |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.72 sec: 1.18x faster                                              |
| asyncio_tcp                | 614 ms                                                      | 524 ms: 1.17x faster                                                |
| sqlite_synth               | 1.79 us                                                     | 1.55 us: 1.16x faster                                               |
| unpickle_pure_python       | 152 us                                                      | 132 us: 1.16x faster                                                |
| sqlglot_transpile          | 1.15 ms                                                     | 993 us: 1.15x faster                                                |
| richards                   | 30.8 ms                                                     | 26.7 ms: 1.15x faster                                               |
| deepcopy_memo              | 25.5 us                                                     | 22.1 us: 1.15x faster                                               |
| sympy_str                  | 184 ms                                                      | 161 ms: 1.15x faster                                                |
| pickle_pure_python         | 207 us                                                      | 184 us: 1.13x faster                                                |
| regex_compile              | 90.8 ms                                                     | 81.1 ms: 1.12x faster                                               |
| chaos                      | 46.8 ms                                                     | 42.0 ms: 1.11x faster                                               |
| sympy_expand               | 299 ms                                                      | 269 ms: 1.11x faster                                                |
| tomli_loads                | 1.42 sec                                                    | 1.28 sec: 1.11x faster                                              |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 450 ms: 1.10x faster                                                |
| coroutines                 | 14.7 ms                                                     | 13.4 ms: 1.10x faster                                               |
| chameleon                  | 5.35 ms                                                     | 4.89 ms: 1.09x faster                                               |
| nqueens                    | 66.1 ms                                                     | 60.9 ms: 1.09x faster                                               |
| async_tree_memoization     | 367 ms                                                      | 338 ms: 1.08x faster                                                |
| go                         | 98.8 ms                                                     | 91.3 ms: 1.08x faster                                               |
| deepcopy                   | 242 us                                                      | 224 us: 1.08x faster                                                |
| logging_format             | 7.06 us                                                     | 6.53 us: 1.08x faster                                               |
| unpack_sequence            | 47.0 ns                                                     | 43.5 ns: 1.08x faster                                               |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.40 ms: 1.08x faster                                               |
| logging_simple             | 6.60 us                                                     | 6.12 us: 1.08x faster                                               |
| hexiom                     | 4.51 ms                                                     | 4.18 ms: 1.08x faster                                               |
| nbody                      | 69.3 ms                                                     | 64.6 ms: 1.07x faster                                               |
| crypto_pyaes               | 48.2 ms                                                     | 45.1 ms: 1.07x faster                                               |
| dulwich_log                | 44.1 ms                                                     | 41.4 ms: 1.06x faster                                               |
| async_tree_none_tg         | 299 ms                                                      | 281 ms: 1.06x faster                                                |
| sympy_integrate            | 13.7 ms                                                     | 12.9 ms: 1.06x faster                                               |
| float                      | 54.4 ms                                                     | 51.3 ms: 1.06x faster                                               |
| scimark_lu                 | 62.3 ms                                                     | 59.1 ms: 1.05x faster                                               |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 479 ms: 1.05x faster                                                |
| sqlglot_normalize          | 191 ms                                                      | 182 ms: 1.05x faster                                                |
| async_tree_io              | 753 ms                                                      | 721 ms: 1.04x faster                                                |
| async_tree_memoization_tg  | 380 ms                                                      | 364 ms: 1.04x faster                                                |
| pprint_pformat             | 1.06 sec                                                    | 1.02 sec: 1.04x faster                                              |
| pprint_safe_repr           | 519 ms                                                      | 498 ms: 1.04x faster                                                |
| async_tree_io_tg           | 795 ms                                                      | 767 ms: 1.04x faster                                                |
| pycparser                  | 705 ms                                                      | 682 ms: 1.03x faster                                                |
| deepcopy_reduce            | 2.07 us                                                     | 2.01 us: 1.03x faster                                               |
| xml_etree_parse            | 94.5 ms                                                     | 91.6 ms: 1.03x faster                                               |
| pyflate                    | 305 ms                                                      | 295 ms: 1.03x faster                                                |
| fannkuch                   | 248 ms                                                      | 242 ms: 1.02x faster                                                |
| xml_etree_iterparse        | 63.0 ms                                                     | 61.5 ms: 1.02x faster                                               |
| sqlglot_optimize           | 35.1 ms                                                     | 34.6 ms: 1.01x faster                                               |
| docutils                   | 1.59 sec                                                    | 1.57 sec: 1.01x faster                                              |
| regex_dna                  | 121 ms                                                      | 120 ms: 1.01x faster                                                |
| xml_etree_process          | 37.0 ms                                                     | 36.8 ms: 1.01x faster                                               |
| meteor_contest             | 75.0 ms                                                     | 75.4 ms: 1.01x slower                                               |
| pidigits                   | 149 ms                                                      | 150 ms: 1.01x slower                                                |
| scimark_monte_carlo        | 44.6 ms                                                     | 45.4 ms: 1.02x slower                                               |
| pickle_dict                | 17.8 us                                                     | 18.1 us: 1.02x slower                                               |
| gc_traversal               | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                               |
| bench_thread_pool          | 847 us                                                      | 869 us: 1.03x slower                                                |
| unpickle_list              | 2.57 us                                                     | 2.65 us: 1.03x slower                                               |
| scimark_fft                | 181 ms                                                      | 188 ms: 1.04x slower                                                |
| create_gc_cycles           | 706 us                                                      | 732 us: 1.04x slower                                                |
| regex_effbot               | 1.52 ms                                                     | 1.58 ms: 1.04x slower                                               |
| json_loads                 | 12.9 us                                                     | 13.4 us: 1.04x slower                                               |
| xml_etree_generate         | 52.2 ms                                                     | 54.5 ms: 1.04x slower                                               |
| unpickle                   | 7.82 us                                                     | 8.17 us: 1.04x slower                                               |
| dask                       | 262 ms                                                      | 275 ms: 1.05x slower                                                |
| pickle                     | 6.53 us                                                     | 6.86 us: 1.05x slower                                               |
| 2to3                       | 207 ms                                                      | 218 ms: 1.05x slower                                                |
| scimark_sor                | 76.4 ms                                                     | 80.7 ms: 1.06x slower                                               |
| coverage                   | 43.0 ms                                                     | 45.9 ms: 1.07x slower                                               |
| bench_mp_pool              | 61.1 ms                                                     | 66.1 ms: 1.08x slower                                               |
| tornado_http               | 89.9 ms                                                     | 97.5 ms: 1.08x slower                                               |
| python_startup             | 18.8 ms                                                     | 20.7 ms: 1.10x slower                                               |
| pathlib                    | 69.4 ms                                                     | 81.0 ms: 1.17x slower                                               |
| telco                      | 3.93 ms                                                     | 4.64 ms: 1.18x slower                                               |
| pickle_list                | 2.68 us                                                     | 3.19 us: 1.19x slower                                               |
| python_startup_no_site     | 15.5 ms                                                     | 18.7 ms: 1.20x slower                                               |
| mypy2                      | 226 ms                                                      | 294 ms: 1.30x slower                                                |
| regex_v8                   | 13.7 ms                                                     | 17.9 ms: 1.30x slower                                               |
| async_generators           | 181 ms                                                      | 236 ms: 1.31x slower                                                |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                        |

Benchmark hidden because not significant (1): json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
