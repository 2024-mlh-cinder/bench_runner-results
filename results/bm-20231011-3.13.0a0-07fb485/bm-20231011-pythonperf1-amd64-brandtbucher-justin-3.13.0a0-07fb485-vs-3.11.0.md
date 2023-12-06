
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 07fb485
- commit date: 2023-10-11
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.71 sec: 1.07x slower                                             |
| Geometric mean | (ref)                                                       | 1.03x slower                                                       |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                               |
| nbody          | 70.0 ms                                                     | 86.4 ms: 1.23x slower                                              |
| Geometric mean | (ref)                                                       | 1.08x slower                                                       |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 121 ms: 1.05x slower                                               |
| regex_effbot   | 1.50 ms                                                     | 1.61 ms: 1.08x slower                                              |
| regex_compile  | 90.6 ms                                                     | 99.0 ms: 1.09x slower                                              |
| regex_v8       | 13.8 ms                                                     | 16.9 ms: 1.22x slower                                              |
| Geometric mean | (ref)                                                       | 1.11x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 6.00 ms: 1.26x faster                                              |
| xml_etree_parse      | 95.9 ms                                                     | 92.9 ms: 1.03x faster                                              |
| unpickle             | 8.09 us                                                     | 8.23 us: 1.02x slower                                              |
| pickle_dict          | 18.5 us                                                     | 18.9 us: 1.02x slower                                              |
| pickle_list          | 2.68 us                                                     | 2.82 us: 1.05x slower                                              |
| tomli_loads          | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                             |
| unpickle_list        | 2.55 us                                                     | 2.71 us: 1.06x slower                                              |
| json_loads           | 12.9 us                                                     | 13.9 us: 1.08x slower                                              |
| xml_etree_iterparse  | 62.6 ms                                                     | 67.4 ms: 1.08x slower                                              |
| pickle               | 6.61 us                                                     | 7.34 us: 1.11x slower                                              |
| unpickle_pure_python | 152 us                                                      | 172 us: 1.13x slower                                               |
| pickle_pure_python   | 200 us                                                      | 227 us: 1.14x slower                                               |
| xml_etree_generate   | 52.2 ms                                                     | 62.8 ms: 1.20x slower                                              |
| xml_etree_process    | 37.1 ms                                                     | 45.2 ms: 1.22x slower                                              |
| Geometric mean       | (ref)                                                       | 1.06x slower                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup | 18.7 ms                                                     | 19.4 ms: 1.04x slower                                              |
| Geometric mean | (ref)                                                       | 1.02x slower                                                       |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.91 ms: 1.05x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231011-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-07fb485 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 101 us: 3.17x faster                                               |
| asyncio_tcp              | 699 ms                                                      | 488 ms: 1.43x faster                                               |
| json_dumps               | 7.56 ms                                                     | 6.00 ms: 1.26x faster                                              |
| coverage                 | 55.9 ms                                                     | 47.7 ms: 1.17x faster                                              |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.82 sec: 1.16x faster                                             |
| async_tree_none          | 320 ms                                                      | 289 ms: 1.11x faster                                               |
| json                     | 3.25 ms                                                     | 2.94 ms: 1.11x faster                                              |
| mdp                      | 1.67 sec                                                    | 1.53 sec: 1.09x faster                                             |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 477 ms: 1.05x faster                                               |
| mako                     | 7.26 ms                                                     | 6.91 ms: 1.05x faster                                              |
| xml_etree_parse          | 95.9 ms                                                     | 92.9 ms: 1.03x faster                                              |
| generators               | 33.8 ms                                                     | 34.2 ms: 1.01x slower                                              |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                               |
| unpickle                 | 8.09 us                                                     | 8.23 us: 1.02x slower                                              |
| pickle_dict              | 18.5 us                                                     | 18.9 us: 1.02x slower                                              |
| sqlite_synth             | 1.68 us                                                     | 1.73 us: 1.03x slower                                              |
| richards_super           | 37.5 ms                                                     | 38.6 ms: 1.03x slower                                              |
| gc_traversal             | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                              |
| sqlglot_parse            | 952 us                                                      | 984 us: 1.03x slower                                               |
| bench_thread_pool        | 852 us                                                      | 881 us: 1.03x slower                                               |
| dulwich_log              | 44.5 ms                                                     | 46.1 ms: 1.04x slower                                              |
| python_startup           | 18.7 ms                                                     | 19.4 ms: 1.04x slower                                              |
| create_gc_cycles         | 693 us                                                      | 722 us: 1.04x slower                                               |
| nqueens                  | 64.9 ms                                                     | 67.8 ms: 1.04x slower                                              |
| regex_dna                | 115 ms                                                      | 121 ms: 1.05x slower                                               |
| pickle_list              | 2.68 us                                                     | 2.82 us: 1.05x slower                                              |
| tomli_loads              | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                             |
| bench_mp_pool            | 62.5 ms                                                     | 65.8 ms: 1.05x slower                                              |
| sqlglot_transpile        | 1.16 ms                                                     | 1.23 ms: 1.05x slower                                              |
| unpack_sequence          | 46.1 ns                                                     | 48.6 ns: 1.06x slower                                              |
| comprehensions           | 15.9 us                                                     | 16.8 us: 1.06x slower                                              |
| unpickle_list            | 2.55 us                                                     | 2.71 us: 1.06x slower                                              |
| fannkuch                 | 252 ms                                                      | 269 ms: 1.07x slower                                               |
| docutils                 | 1.60 sec                                                    | 1.71 sec: 1.07x slower                                             |
| chaos                    | 47.1 ms                                                     | 50.4 ms: 1.07x slower                                              |
| crypto_pyaes             | 47.6 ms                                                     | 50.9 ms: 1.07x slower                                              |
| meteor_contest           | 74.7 ms                                                     | 80.1 ms: 1.07x slower                                              |
| logging_simple           | 6.61 us                                                     | 7.09 us: 1.07x slower                                              |
| regex_effbot             | 1.50 ms                                                     | 1.61 ms: 1.08x slower                                              |
| json_loads               | 12.9 us                                                     | 13.9 us: 1.08x slower                                              |
| logging_format           | 7.01 us                                                     | 7.55 us: 1.08x slower                                              |
| xml_etree_iterparse      | 62.6 ms                                                     | 67.4 ms: 1.08x slower                                              |
| regex_compile            | 90.6 ms                                                     | 99.0 ms: 1.09x slower                                              |
| deltablue                | 2.61 ms                                                     | 2.87 ms: 1.10x slower                                              |
| sqlglot_normalize        | 190 ms                                                      | 210 ms: 1.10x slower                                               |
| pathlib                  | 71.4 ms                                                     | 78.9 ms: 1.11x slower                                              |
| pickle                   | 6.61 us                                                     | 7.34 us: 1.11x slower                                              |
| pycparser                | 691 ms                                                      | 771 ms: 1.12x slower                                               |
| sqlglot_optimize         | 34.9 ms                                                     | 39.0 ms: 1.12x slower                                              |
| deepcopy                 | 246 us                                                      | 276 us: 1.12x slower                                               |
| unpickle_pure_python     | 152 us                                                      | 172 us: 1.13x slower                                               |
| pickle_pure_python       | 200 us                                                      | 227 us: 1.14x slower                                               |
| hexiom                   | 4.55 ms                                                     | 5.21 ms: 1.14x slower                                              |
| richards                 | 30.6 ms                                                     | 35.0 ms: 1.15x slower                                              |
| scimark_fft              | 178 ms                                                      | 205 ms: 1.15x slower                                               |
| deepcopy_reduce          | 2.07 us                                                     | 2.39 us: 1.15x slower                                              |
| scimark_monte_carlo      | 44.6 ms                                                     | 51.5 ms: 1.15x slower                                              |
| pyflate                  | 304 ms                                                      | 352 ms: 1.16x slower                                               |
| go                       | 97.3 ms                                                     | 113 ms: 1.16x slower                                               |
| pprint_safe_repr         | 512 ms                                                      | 599 ms: 1.17x slower                                               |
| pprint_pformat           | 1.04 sec                                                    | 1.22 sec: 1.17x slower                                             |
| spectral_norm            | 67.9 ms                                                     | 80.9 ms: 1.19x slower                                              |
| xml_etree_generate       | 52.2 ms                                                     | 62.8 ms: 1.20x slower                                              |
| scimark_lu               | 63.5 ms                                                     | 76.7 ms: 1.21x slower                                              |
| xml_etree_process        | 37.1 ms                                                     | 45.2 ms: 1.22x slower                                              |
| regex_v8                 | 13.8 ms                                                     | 16.9 ms: 1.22x slower                                              |
| nbody                    | 70.0 ms                                                     | 86.4 ms: 1.23x slower                                              |
| telco                    | 3.90 ms                                                     | 4.83 ms: 1.24x slower                                              |
| deepcopy_memo            | 25.2 us                                                     | 31.9 us: 1.27x slower                                              |
| logging_silent           | 69.8 ns                                                     | 91.1 ns: 1.30x slower                                              |
| coroutines               | 14.6 ms                                                     | 19.1 ms: 1.31x slower                                              |
| scimark_sor              | 75.6 ms                                                     | 105 ms: 1.39x slower                                               |
| async_generators         | 178 ms                                                      | 269 ms: 1.51x slower                                               |
| Geometric mean           | (ref)                                                       | 1.05x slower                                                       |

Benchmark hidden because not significant (8): async_tree_memoization, async_tree_io, raytrace, tornado_http, float, scimark_sparse_mat_mult, python_startup_no_site, mypy2
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
