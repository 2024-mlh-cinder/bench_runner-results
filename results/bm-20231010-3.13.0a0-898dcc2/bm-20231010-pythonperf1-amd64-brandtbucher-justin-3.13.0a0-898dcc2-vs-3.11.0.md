
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 898dcc2
- commit date: 2023-10-10
- overall geometric mean: 1.04x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                             |
| Geometric mean | (ref)                                                       | 1.03x slower                                                       |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                               |
| nbody          | 70.0 ms                                                     | 84.9 ms: 1.21x slower                                              |
| Geometric mean | (ref)                                                       | 1.07x slower                                                       |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 119 ms: 1.03x slower                                               |
| regex_effbot   | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                              |
| regex_compile  | 90.6 ms                                                     | 98.1 ms: 1.08x slower                                              |
| regex_v8       | 13.8 ms                                                     | 15.2 ms: 1.10x slower                                              |
| Geometric mean | (ref)                                                       | 1.07x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 6.06 ms: 1.25x faster                                              |
| xml_etree_parse      | 95.9 ms                                                     | 93.2 ms: 1.03x faster                                              |
| tomli_loads          | 1.41 sec                                                    | 1.40 sec: 1.01x faster                                             |
| unpickle             | 8.09 us                                                     | 8.17 us: 1.01x slower                                              |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                              |
| unpickle_list        | 2.55 us                                                     | 2.69 us: 1.06x slower                                              |
| pickle               | 6.61 us                                                     | 7.11 us: 1.08x slower                                              |
| pickle_list          | 2.68 us                                                     | 2.94 us: 1.10x slower                                              |
| xml_etree_iterparse  | 62.6 ms                                                     | 70.2 ms: 1.12x slower                                              |
| pickle_pure_python   | 200 us                                                      | 225 us: 1.13x slower                                               |
| unpickle_pure_python | 152 us                                                      | 175 us: 1.16x slower                                               |
| xml_etree_generate   | 52.2 ms                                                     | 64.1 ms: 1.23x slower                                              |
| xml_etree_process    | 37.1 ms                                                     | 45.9 ms: 1.24x slower                                              |
| Geometric mean       | (ref)                                                       | 1.06x slower                                                       |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.6 ms: 1.05x slower                                              |
| python_startup         | 18.7 ms                                                     | 20.0 ms: 1.07x slower                                              |
| Geometric mean         | (ref)                                                       | 1.06x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.72 ms: 1.08x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 101 us: 3.18x faster                                               |
| asyncio_tcp              | 699 ms                                                      | 471 ms: 1.48x faster                                               |
| json_dumps               | 7.56 ms                                                     | 6.06 ms: 1.25x faster                                              |
| coverage                 | 55.9 ms                                                     | 46.3 ms: 1.21x faster                                              |
| mdp                      | 1.67 sec                                                    | 1.44 sec: 1.16x faster                                             |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.88 sec: 1.12x faster                                             |
| async_tree_none          | 320 ms                                                      | 288 ms: 1.11x faster                                               |
| mako                     | 7.26 ms                                                     | 6.72 ms: 1.08x faster                                              |
| json                     | 3.25 ms                                                     | 3.03 ms: 1.08x faster                                              |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.42 ms: 1.06x faster                                              |
| deltablue                | 2.61 ms                                                     | 2.47 ms: 1.06x faster                                              |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 477 ms: 1.05x faster                                               |
| xml_etree_parse          | 95.9 ms                                                     | 93.2 ms: 1.03x faster                                              |
| tomli_loads              | 1.41 sec                                                    | 1.40 sec: 1.01x faster                                             |
| comprehensions           | 15.9 us                                                     | 15.8 us: 1.01x faster                                              |
| unpickle                 | 8.09 us                                                     | 8.17 us: 1.01x slower                                              |
| sqlite_synth             | 1.68 us                                                     | 1.70 us: 1.01x slower                                              |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                               |
| crypto_pyaes             | 47.6 ms                                                     | 48.3 ms: 1.02x slower                                              |
| gc_traversal             | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                              |
| nqueens                  | 64.9 ms                                                     | 66.4 ms: 1.02x slower                                              |
| sqlglot_parse            | 952 us                                                      | 976 us: 1.03x slower                                               |
| dulwich_log              | 44.5 ms                                                     | 45.7 ms: 1.03x slower                                              |
| richards_super           | 37.5 ms                                                     | 38.6 ms: 1.03x slower                                              |
| regex_dna                | 115 ms                                                      | 119 ms: 1.03x slower                                               |
| bench_thread_pool        | 852 us                                                      | 880 us: 1.03x slower                                               |
| fannkuch                 | 252 ms                                                      | 261 ms: 1.03x slower                                               |
| chaos                    | 47.1 ms                                                     | 48.9 ms: 1.04x slower                                              |
| sqlglot_transpile        | 1.16 ms                                                     | 1.22 ms: 1.05x slower                                              |
| python_startup_no_site   | 15.9 ms                                                     | 16.6 ms: 1.05x slower                                              |
| unpack_sequence          | 46.1 ns                                                     | 48.4 ns: 1.05x slower                                              |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                              |
| create_gc_cycles         | 693 us                                                      | 729 us: 1.05x slower                                               |
| logging_simple           | 6.61 us                                                     | 6.98 us: 1.06x slower                                              |
| unpickle_list            | 2.55 us                                                     | 2.69 us: 1.06x slower                                              |
| regex_effbot             | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                              |
| logging_format           | 7.01 us                                                     | 7.42 us: 1.06x slower                                              |
| docutils                 | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                             |
| hexiom                   | 4.55 ms                                                     | 4.83 ms: 1.06x slower                                              |
| meteor_contest           | 74.7 ms                                                     | 79.3 ms: 1.06x slower                                              |
| python_startup           | 18.7 ms                                                     | 20.0 ms: 1.07x slower                                              |
| pickle                   | 6.61 us                                                     | 7.11 us: 1.08x slower                                              |
| regex_compile            | 90.6 ms                                                     | 98.1 ms: 1.08x slower                                              |
| sqlglot_normalize        | 190 ms                                                      | 208 ms: 1.09x slower                                               |
| regex_v8                 | 13.8 ms                                                     | 15.2 ms: 1.10x slower                                              |
| pickle_list              | 2.68 us                                                     | 2.94 us: 1.10x slower                                              |
| pathlib                  | 71.4 ms                                                     | 78.4 ms: 1.10x slower                                              |
| bench_mp_pool            | 62.5 ms                                                     | 69.3 ms: 1.11x slower                                              |
| sqlglot_optimize         | 34.9 ms                                                     | 38.7 ms: 1.11x slower                                              |
| scimark_fft              | 178 ms                                                      | 200 ms: 1.12x slower                                               |
| xml_etree_iterparse      | 62.6 ms                                                     | 70.2 ms: 1.12x slower                                              |
| pycparser                | 691 ms                                                      | 776 ms: 1.12x slower                                               |
| pyflate                  | 304 ms                                                      | 342 ms: 1.12x slower                                               |
| pickle_pure_python       | 200 us                                                      | 225 us: 1.13x slower                                               |
| scimark_monte_carlo      | 44.6 ms                                                     | 50.4 ms: 1.13x slower                                              |
| go                       | 97.3 ms                                                     | 110 ms: 1.13x slower                                               |
| deepcopy                 | 246 us                                                      | 279 us: 1.14x slower                                               |
| pprint_safe_repr         | 512 ms                                                      | 582 ms: 1.14x slower                                               |
| richards                 | 30.6 ms                                                     | 34.8 ms: 1.14x slower                                              |
| pprint_pformat           | 1.04 sec                                                    | 1.20 sec: 1.15x slower                                             |
| deepcopy_reduce          | 2.07 us                                                     | 2.39 us: 1.15x slower                                              |
| unpickle_pure_python     | 152 us                                                      | 175 us: 1.16x slower                                               |
| scimark_lu               | 63.5 ms                                                     | 75.0 ms: 1.18x slower                                              |
| spectral_norm            | 67.9 ms                                                     | 80.9 ms: 1.19x slower                                              |
| nbody                    | 70.0 ms                                                     | 84.9 ms: 1.21x slower                                              |
| telco                    | 3.90 ms                                                     | 4.77 ms: 1.22x slower                                              |
| xml_etree_generate       | 52.2 ms                                                     | 64.1 ms: 1.23x slower                                              |
| xml_etree_process        | 37.1 ms                                                     | 45.9 ms: 1.24x slower                                              |
| deepcopy_memo            | 25.2 us                                                     | 31.8 us: 1.26x slower                                              |
| coroutines               | 14.6 ms                                                     | 18.9 ms: 1.29x slower                                              |
| logging_silent           | 69.8 ns                                                     | 90.9 ns: 1.30x slower                                              |
| scimark_sor              | 75.6 ms                                                     | 103 ms: 1.36x slower                                               |
| async_generators         | 178 ms                                                      | 269 ms: 1.52x slower                                               |
| Geometric mean           | (ref)                                                       | 1.04x slower                                                       |

Benchmark hidden because not significant (8): pickle_dict, async_tree_io, async_tree_memoization, tornado_http, float, mypy2, raytrace, generators
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
