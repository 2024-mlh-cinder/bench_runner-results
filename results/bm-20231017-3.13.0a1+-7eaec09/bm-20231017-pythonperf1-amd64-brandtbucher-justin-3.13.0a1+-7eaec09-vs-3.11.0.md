
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.04x slower
- HPT reliability: 99.83%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                              |
| Geometric mean | (ref)                                                       | 1.03x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 54.6 ms                                                     | 52.0 ms: 1.05x faster                                               |
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                                |
| nbody          | 70.0 ms                                                     | 81.7 ms: 1.17x slower                                               |
| Geometric mean | (ref)                                                       | 1.04x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 119 ms: 1.03x slower                                                |
| regex_compile  | 90.6 ms                                                     | 95.7 ms: 1.06x slower                                               |
| regex_effbot   | 1.50 ms                                                     | 1.61 ms: 1.07x slower                                               |
| regex_v8       | 13.8 ms                                                     | 21.4 ms: 1.54x slower                                               |
| Geometric mean | (ref)                                                       | 1.16x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.98 ms: 1.26x faster                                               |
| xml_etree_parse      | 95.9 ms                                                     | 92.5 ms: 1.04x faster                                               |
| tomli_loads          | 1.41 sec                                                    | 1.38 sec: 1.03x faster                                              |
| unpickle             | 8.09 us                                                     | 8.16 us: 1.01x slower                                               |
| json_loads           | 12.9 us                                                     | 13.7 us: 1.06x slower                                               |
| unpickle_list        | 2.55 us                                                     | 2.71 us: 1.06x slower                                               |
| pickle               | 6.61 us                                                     | 7.04 us: 1.07x slower                                               |
| pickle_list          | 2.68 us                                                     | 2.86 us: 1.07x slower                                               |
| xml_etree_iterparse  | 62.6 ms                                                     | 68.1 ms: 1.09x slower                                               |
| unpickle_pure_python | 152 us                                                      | 170 us: 1.12x slower                                                |
| pickle_pure_python   | 200 us                                                      | 227 us: 1.14x slower                                                |
| xml_etree_generate   | 52.2 ms                                                     | 62.2 ms: 1.19x slower                                               |
| xml_etree_process    | 37.1 ms                                                     | 44.8 ms: 1.21x slower                                               |
| Geometric mean       | (ref)                                                       | 1.05x slower                                                        |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                               |
| python_startup         | 18.7 ms                                                     | 19.6 ms: 1.05x slower                                               |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.39 ms: 1.14x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 107 us: 3.00x faster                                                |
| asyncio_tcp              | 699 ms                                                      | 478 ms: 1.46x faster                                                |
| json_dumps               | 7.56 ms                                                     | 5.98 ms: 1.26x faster                                               |
| coverage                 | 55.9 ms                                                     | 45.8 ms: 1.22x faster                                               |
| mdp                      | 1.67 sec                                                    | 1.44 sec: 1.16x faster                                              |
| mako                     | 7.26 ms                                                     | 6.39 ms: 1.14x faster                                               |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.87 sec: 1.13x faster                                              |
| deltablue                | 2.61 ms                                                     | 2.34 ms: 1.12x faster                                               |
| async_tree_none          | 320 ms                                                      | 290 ms: 1.10x faster                                                |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.34 ms: 1.10x faster                                               |
| json                     | 3.25 ms                                                     | 3.00 ms: 1.09x faster                                               |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 476 ms: 1.05x faster                                                |
| float                    | 54.6 ms                                                     | 52.0 ms: 1.05x faster                                               |
| comprehensions           | 15.9 us                                                     | 15.3 us: 1.04x faster                                               |
| xml_etree_parse          | 95.9 ms                                                     | 92.5 ms: 1.04x faster                                               |
| tomli_loads              | 1.41 sec                                                    | 1.38 sec: 1.03x faster                                              |
| crypto_pyaes             | 47.6 ms                                                     | 46.6 ms: 1.02x faster                                               |
| async_tree_io            | 779 ms                                                      | 767 ms: 1.02x faster                                                |
| fannkuch                 | 252 ms                                                      | 249 ms: 1.01x faster                                                |
| sqlite_synth             | 1.68 us                                                     | 1.66 us: 1.01x faster                                               |
| generators               | 33.8 ms                                                     | 33.5 ms: 1.01x faster                                               |
| raytrace                 | 211 ms                                                      | 209 ms: 1.01x faster                                                |
| mypy2                    | 229 ms                                                      | 230 ms: 1.00x slower                                                |
| hexiom                   | 4.55 ms                                                     | 4.58 ms: 1.00x slower                                               |
| nqueens                  | 64.9 ms                                                     | 65.4 ms: 1.01x slower                                               |
| unpickle                 | 8.09 us                                                     | 8.16 us: 1.01x slower                                               |
| python_startup_no_site   | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                               |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                                |
| richards_super           | 37.5 ms                                                     | 38.4 ms: 1.02x slower                                               |
| regex_dna                | 115 ms                                                      | 119 ms: 1.03x slower                                                |
| bench_thread_pool        | 852 us                                                      | 877 us: 1.03x slower                                                |
| sqlglot_parse            | 952 us                                                      | 979 us: 1.03x slower                                                |
| chaos                    | 47.1 ms                                                     | 48.6 ms: 1.03x slower                                               |
| gc_traversal             | 1.46 ms                                                     | 1.51 ms: 1.03x slower                                               |
| meteor_contest           | 74.7 ms                                                     | 77.6 ms: 1.04x slower                                               |
| dulwich_log              | 44.5 ms                                                     | 46.3 ms: 1.04x slower                                               |
| python_startup           | 18.7 ms                                                     | 19.6 ms: 1.05x slower                                               |
| unpack_sequence          | 46.1 ns                                                     | 48.4 ns: 1.05x slower                                               |
| logging_simple           | 6.61 us                                                     | 6.95 us: 1.05x slower                                               |
| sqlglot_transpile        | 1.16 ms                                                     | 1.22 ms: 1.05x slower                                               |
| create_gc_cycles         | 693 us                                                      | 730 us: 1.05x slower                                                |
| logging_format           | 7.01 us                                                     | 7.41 us: 1.06x slower                                               |
| regex_compile            | 90.6 ms                                                     | 95.7 ms: 1.06x slower                                               |
| json_loads               | 12.9 us                                                     | 13.7 us: 1.06x slower                                               |
| bench_mp_pool            | 62.5 ms                                                     | 66.3 ms: 1.06x slower                                               |
| unpickle_list            | 2.55 us                                                     | 2.71 us: 1.06x slower                                               |
| docutils                 | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                              |
| pickle                   | 6.61 us                                                     | 7.04 us: 1.07x slower                                               |
| pickle_list              | 2.68 us                                                     | 2.86 us: 1.07x slower                                               |
| regex_effbot             | 1.50 ms                                                     | 1.61 ms: 1.07x slower                                               |
| scimark_fft              | 178 ms                                                      | 192 ms: 1.08x slower                                                |
| sqlglot_normalize        | 190 ms                                                      | 207 ms: 1.09x slower                                                |
| xml_etree_iterparse      | 62.6 ms                                                     | 68.1 ms: 1.09x slower                                               |
| pyflate                  | 304 ms                                                      | 331 ms: 1.09x slower                                                |
| sqlglot_optimize         | 34.9 ms                                                     | 38.9 ms: 1.12x slower                                               |
| pathlib                  | 71.4 ms                                                     | 79.8 ms: 1.12x slower                                               |
| scimark_monte_carlo      | 44.6 ms                                                     | 50.1 ms: 1.12x slower                                               |
| go                       | 97.3 ms                                                     | 109 ms: 1.12x slower                                                |
| unpickle_pure_python     | 152 us                                                      | 170 us: 1.12x slower                                                |
| pprint_pformat           | 1.04 sec                                                    | 1.17 sec: 1.12x slower                                              |
| deepcopy                 | 246 us                                                      | 277 us: 1.13x slower                                                |
| richards                 | 30.6 ms                                                     | 34.5 ms: 1.13x slower                                               |
| pprint_safe_repr         | 512 ms                                                      | 577 ms: 1.13x slower                                                |
| pickle_pure_python       | 200 us                                                      | 227 us: 1.14x slower                                                |
| deepcopy_reduce          | 2.07 us                                                     | 2.41 us: 1.16x slower                                               |
| nbody                    | 70.0 ms                                                     | 81.7 ms: 1.17x slower                                               |
| pycparser                | 691 ms                                                      | 808 ms: 1.17x slower                                                |
| spectral_norm            | 67.9 ms                                                     | 80.1 ms: 1.18x slower                                               |
| scimark_lu               | 63.5 ms                                                     | 75.3 ms: 1.19x slower                                               |
| xml_etree_generate       | 52.2 ms                                                     | 62.2 ms: 1.19x slower                                               |
| deepcopy_memo            | 25.2 us                                                     | 30.2 us: 1.20x slower                                               |
| telco                    | 3.90 ms                                                     | 4.69 ms: 1.20x slower                                               |
| xml_etree_process        | 37.1 ms                                                     | 44.8 ms: 1.21x slower                                               |
| logging_silent           | 69.8 ns                                                     | 92.1 ns: 1.32x slower                                               |
| coroutines               | 14.6 ms                                                     | 19.4 ms: 1.33x slower                                               |
| scimark_sor              | 75.6 ms                                                     | 105 ms: 1.38x slower                                                |
| async_generators         | 178 ms                                                      | 274 ms: 1.54x slower                                                |
| regex_v8                 | 13.8 ms                                                     | 21.4 ms: 1.54x slower                                               |
| Geometric mean           | (ref)                                                       | 1.04x slower                                                        |

Benchmark hidden because not significant (3): async_tree_memoization, tornado_http, pickle_dict
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.83% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
