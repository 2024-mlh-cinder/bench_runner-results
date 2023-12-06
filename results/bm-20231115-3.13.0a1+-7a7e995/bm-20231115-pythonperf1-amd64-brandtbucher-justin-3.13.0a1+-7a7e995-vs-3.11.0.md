
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.08x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 213 ms: 1.03x slower                                                |
| chameleon      | 5.35 ms                                                     | 4.74 ms: 1.13x faster                                               |
| docutils       | 1.59 sec                                                    | 1.57 sec: 1.01x faster                                              |
| tornado_http   | 89.9 ms                                                     | 86.7 ms: 1.04x faster                                               |
| Geometric mean | (ref)                                                       | 1.04x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 268 ms: 1.17x faster                                                |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 451 ms: 1.10x faster                                                |
| async_tree_memoization     | 367 ms                                                      | 337 ms: 1.09x faster                                                |
| async_tree_none_tg         | 299 ms                                                      | 283 ms: 1.05x faster                                                |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 477 ms: 1.05x faster                                                |
| async_tree_memoization_tg  | 380 ms                                                      | 361 ms: 1.05x faster                                                |
| async_tree_io_tg           | 795 ms                                                      | 761 ms: 1.04x faster                                                |
| async_tree_io              | 753 ms                                                      | 724 ms: 1.04x faster                                                |
| Geometric mean             | (ref)                                                       | 1.07x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 50.2 ms: 1.08x faster                                               |
| nbody          | 69.3 ms                                                     | 66.6 ms: 1.04x faster                                               |
| pidigits       | 149 ms                                                      | 150 ms: 1.01x slower                                                |
| Geometric mean | (ref)                                                       | 1.04x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 79.5 ms: 1.14x faster                                               |
| regex_effbot   | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                               |
| regex_v8       | 13.7 ms                                                     | 15.4 ms: 1.12x slower                                               |
| Geometric mean | (ref)                                                       | 1.01x slower                                                        |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.67 ms: 1.39x faster                                               |
| unpickle_pure_python | 152 us                                                      | 130 us: 1.17x faster                                                |
| pickle_pure_python   | 207 us                                                      | 180 us: 1.15x faster                                                |
| tomli_loads          | 1.42 sec                                                    | 1.27 sec: 1.12x faster                                              |
| xml_etree_parse      | 94.5 ms                                                     | 91.8 ms: 1.03x faster                                               |
| xml_etree_process    | 37.0 ms                                                     | 36.2 ms: 1.02x faster                                               |
| xml_etree_iterparse  | 63.0 ms                                                     | 62.1 ms: 1.01x faster                                               |
| xml_etree_generate   | 52.2 ms                                                     | 53.3 ms: 1.02x slower                                               |
| unpickle_list        | 2.57 us                                                     | 2.68 us: 1.04x slower                                               |
| pickle_dict          | 17.8 us                                                     | 18.6 us: 1.04x slower                                               |
| unpickle             | 7.82 us                                                     | 8.18 us: 1.05x slower                                               |
| json_loads           | 12.9 us                                                     | 13.9 us: 1.08x slower                                               |
| pickle               | 6.53 us                                                     | 7.22 us: 1.11x slower                                               |
| pickle_list          | 2.68 us                                                     | 3.32 us: 1.24x slower                                               |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.4 ms: 1.08x slower                                               |
| python_startup_no_site | 15.5 ms                                                     | 18.2 ms: 1.17x slower                                               |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.55 ms                                                     | 6.21 ms: 1.22x faster                                               |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 75.2 us: 4.25x faster                                               |
| generators                 | 34.0 ms                                                     | 20.8 ms: 1.63x faster                                               |
| comprehensions             | 15.6 us                                                     | 11.0 us: 1.42x faster                                               |
| json_dumps                 | 7.90 ms                                                     | 5.67 ms: 1.39x faster                                               |
| deltablue                  | 2.63 ms                                                     | 1.98 ms: 1.32x faster                                               |
| asyncio_tcp                | 614 ms                                                      | 469 ms: 1.31x faster                                                |
| richards_super             | 37.9 ms                                                     | 29.1 ms: 1.30x faster                                               |
| logging_silent             | 70.7 ns                                                     | 55.9 ns: 1.27x faster                                               |
| sqlglot_parse              | 939 us                                                      | 754 us: 1.24x faster                                                |
| raytrace                   | 211 ms                                                      | 173 ms: 1.22x faster                                                |
| mako                       | 7.55 ms                                                     | 6.21 ms: 1.22x faster                                               |
| sympy_sum                  | 100.0 ms                                                    | 82.9 ms: 1.21x faster                                               |
| spectral_norm              | 69.9 ms                                                     | 58.3 ms: 1.20x faster                                               |
| mdp                        | 1.73 sec                                                    | 1.45 sec: 1.19x faster                                              |
| richards                   | 30.8 ms                                                     | 25.9 ms: 1.19x faster                                               |
| sqlglot_transpile          | 1.15 ms                                                     | 967 us: 1.19x faster                                                |
| deepcopy_memo              | 25.5 us                                                     | 21.6 us: 1.18x faster                                               |
| unpickle_pure_python       | 152 us                                                      | 130 us: 1.17x faster                                                |
| async_tree_none            | 314 ms                                                      | 268 ms: 1.17x faster                                                |
| sympy_str                  | 184 ms                                                      | 158 ms: 1.17x faster                                                |
| unpack_sequence            | 47.0 ns                                                     | 40.4 ns: 1.16x faster                                               |
| sqlite_synth               | 1.79 us                                                     | 1.55 us: 1.16x faster                                               |
| pickle_pure_python         | 207 us                                                      | 180 us: 1.15x faster                                                |
| chaos                      | 46.8 ms                                                     | 40.7 ms: 1.15x faster                                               |
| scimark_lu                 | 62.3 ms                                                     | 54.4 ms: 1.14x faster                                               |
| regex_compile              | 90.8 ms                                                     | 79.5 ms: 1.14x faster                                               |
| chameleon                  | 5.35 ms                                                     | 4.74 ms: 1.13x faster                                               |
| coroutines                 | 14.7 ms                                                     | 13.0 ms: 1.13x faster                                               |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.31 ms: 1.12x faster                                               |
| tomli_loads                | 1.42 sec                                                    | 1.27 sec: 1.12x faster                                              |
| sympy_expand               | 299 ms                                                      | 268 ms: 1.12x faster                                                |
| deepcopy                   | 242 us                                                      | 218 us: 1.11x faster                                                |
| go                         | 98.8 ms                                                     | 88.8 ms: 1.11x faster                                               |
| nqueens                    | 66.1 ms                                                     | 59.5 ms: 1.11x faster                                               |
| asyncio_tcp_ssl            | 2.02 sec                                                    | 1.83 sec: 1.10x faster                                              |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 451 ms: 1.10x faster                                                |
| async_tree_memoization     | 367 ms                                                      | 337 ms: 1.09x faster                                                |
| hexiom                     | 4.51 ms                                                     | 4.15 ms: 1.09x faster                                               |
| dulwich_log                | 44.1 ms                                                     | 40.7 ms: 1.08x faster                                               |
| float                      | 54.4 ms                                                     | 50.2 ms: 1.08x faster                                               |
| sqlglot_normalize          | 191 ms                                                      | 177 ms: 1.08x faster                                                |
| sympy_integrate            | 13.7 ms                                                     | 12.7 ms: 1.08x faster                                               |
| logging_simple             | 6.60 us                                                     | 6.13 us: 1.08x faster                                               |
| logging_format             | 7.06 us                                                     | 6.58 us: 1.07x faster                                               |
| deepcopy_reduce            | 2.07 us                                                     | 1.94 us: 1.07x faster                                               |
| async_tree_none_tg         | 299 ms                                                      | 283 ms: 1.05x faster                                                |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 477 ms: 1.05x faster                                                |
| sqlglot_optimize           | 35.1 ms                                                     | 33.3 ms: 1.05x faster                                               |
| async_tree_memoization_tg  | 380 ms                                                      | 361 ms: 1.05x faster                                                |
| crypto_pyaes               | 48.2 ms                                                     | 46.1 ms: 1.05x faster                                               |
| async_tree_io_tg           | 795 ms                                                      | 761 ms: 1.04x faster                                                |
| pprint_pformat             | 1.06 sec                                                    | 1.02 sec: 1.04x faster                                              |
| pyflate                    | 305 ms                                                      | 293 ms: 1.04x faster                                                |
| async_tree_io              | 753 ms                                                      | 724 ms: 1.04x faster                                                |
| nbody                      | 69.3 ms                                                     | 66.6 ms: 1.04x faster                                               |
| fannkuch                   | 248 ms                                                      | 239 ms: 1.04x faster                                                |
| pprint_safe_repr           | 519 ms                                                      | 500 ms: 1.04x faster                                                |
| tornado_http               | 89.9 ms                                                     | 86.7 ms: 1.04x faster                                               |
| dask                       | 262 ms                                                      | 254 ms: 1.03x faster                                                |
| xml_etree_parse            | 94.5 ms                                                     | 91.8 ms: 1.03x faster                                               |
| xml_etree_process          | 37.0 ms                                                     | 36.2 ms: 1.02x faster                                               |
| xml_etree_iterparse        | 63.0 ms                                                     | 62.1 ms: 1.01x faster                                               |
| docutils                   | 1.59 sec                                                    | 1.57 sec: 1.01x faster                                              |
| scimark_fft                | 181 ms                                                      | 179 ms: 1.01x faster                                                |
| scimark_monte_carlo        | 44.6 ms                                                     | 44.4 ms: 1.01x faster                                               |
| meteor_contest             | 75.0 ms                                                     | 74.7 ms: 1.00x faster                                               |
| pidigits                   | 149 ms                                                      | 150 ms: 1.01x slower                                                |
| xml_etree_generate         | 52.2 ms                                                     | 53.3 ms: 1.02x slower                                               |
| scimark_sor                | 76.4 ms                                                     | 78.3 ms: 1.03x slower                                               |
| 2to3                       | 207 ms                                                      | 213 ms: 1.03x slower                                                |
| gc_traversal               | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                               |
| coverage                   | 43.0 ms                                                     | 44.3 ms: 1.03x slower                                               |
| create_gc_cycles           | 706 us                                                      | 729 us: 1.03x slower                                                |
| unpickle_list              | 2.57 us                                                     | 2.68 us: 1.04x slower                                               |
| pickle_dict                | 17.8 us                                                     | 18.6 us: 1.04x slower                                               |
| unpickle                   | 7.82 us                                                     | 8.18 us: 1.05x slower                                               |
| bench_mp_pool              | 61.1 ms                                                     | 64.4 ms: 1.05x slower                                               |
| regex_effbot               | 1.52 ms                                                     | 1.61 ms: 1.06x slower                                               |
| json_loads                 | 12.9 us                                                     | 13.9 us: 1.08x slower                                               |
| python_startup             | 18.8 ms                                                     | 20.4 ms: 1.08x slower                                               |
| pathlib                    | 69.4 ms                                                     | 75.4 ms: 1.09x slower                                               |
| pickle                     | 6.53 us                                                     | 7.22 us: 1.11x slower                                               |
| regex_v8                   | 13.7 ms                                                     | 15.4 ms: 1.12x slower                                               |
| telco                      | 3.93 ms                                                     | 4.59 ms: 1.17x slower                                               |
| python_startup_no_site     | 15.5 ms                                                     | 18.2 ms: 1.17x slower                                               |
| pickle_list                | 2.68 us                                                     | 3.32 us: 1.24x slower                                               |
| mypy2                      | 226 ms                                                      | 289 ms: 1.27x slower                                                |
| async_generators           | 181 ms                                                      | 231 ms: 1.28x slower                                                |
| Geometric mean             | (ref)                                                       | 1.08x faster                                                        |

Benchmark hidden because not significant (4): pycparser, bench_thread_pool, json, regex_dna
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.03x
