
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_o2
- machine: windows-amd64
- commit hash: 2a353e9
- commit date: 2023-10-13
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.71 sec: 1.07x slower                                                |
| Geometric mean | (ref)                                                       | 1.04x slower                                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                                  |
| float          | 54.6 ms                                                     | 55.9 ms: 1.02x slower                                                 |
| nbody          | 70.0 ms                                                     | 88.2 ms: 1.26x slower                                                 |
| Geometric mean | (ref)                                                       | 1.09x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 123 ms: 1.07x slower                                                  |
| regex_effbot   | 1.50 ms                                                     | 1.63 ms: 1.09x slower                                                 |
| regex_compile  | 90.6 ms                                                     | 100 ms: 1.10x slower                                                  |
| regex_v8       | 13.8 ms                                                     | 15.9 ms: 1.15x slower                                                 |
| Geometric mean | (ref)                                                       | 1.10x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 6.11 ms: 1.24x faster                                                 |
| xml_etree_parse      | 95.9 ms                                                     | 92.2 ms: 1.04x faster                                                 |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                 |
| tomli_loads          | 1.41 sec                                                    | 1.50 sec: 1.06x slower                                                |
| unpickle_list        | 2.55 us                                                     | 2.71 us: 1.06x slower                                                 |
| pickle_list          | 2.68 us                                                     | 2.86 us: 1.07x slower                                                 |
| xml_etree_iterparse  | 62.6 ms                                                     | 68.0 ms: 1.09x slower                                                 |
| pickle_pure_python   | 200 us                                                      | 224 us: 1.12x slower                                                  |
| unpickle_pure_python | 152 us                                                      | 171 us: 1.12x slower                                                  |
| pickle               | 6.61 us                                                     | 7.44 us: 1.13x slower                                                 |
| xml_etree_generate   | 52.2 ms                                                     | 62.7 ms: 1.20x slower                                                 |
| xml_etree_process    | 37.1 ms                                                     | 44.9 ms: 1.21x slower                                                 |
| Geometric mean       | (ref)                                                       | 1.06x slower                                                          |

Benchmark hidden because not significant (2): pickle_dict, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                                 |
| python_startup         | 18.7 ms                                                     | 19.5 ms: 1.05x slower                                                 |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.86 ms: 1.06x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_o2-3.13.0a0-2a353e9 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 104 us: 3.10x faster                                                  |
| asyncio_tcp              | 699 ms                                                      | 484 ms: 1.44x faster                                                  |
| json_dumps               | 7.56 ms                                                     | 6.11 ms: 1.24x faster                                                 |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.85 sec: 1.14x faster                                                |
| mdp                      | 1.67 sec                                                    | 1.48 sec: 1.13x faster                                                |
| async_tree_none          | 320 ms                                                      | 287 ms: 1.11x faster                                                  |
| json                     | 3.25 ms                                                     | 2.92 ms: 1.11x faster                                                 |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 473 ms: 1.06x faster                                                  |
| mako                     | 7.26 ms                                                     | 6.86 ms: 1.06x faster                                                 |
| xml_etree_parse          | 95.9 ms                                                     | 92.2 ms: 1.04x faster                                                 |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.52 ms: 1.02x faster                                                 |
| async_tree_io            | 779 ms                                                      | 765 ms: 1.02x faster                                                  |
| mypy2                    | 229 ms                                                      | 231 ms: 1.01x slower                                                  |
| raytrace                 | 211 ms                                                      | 213 ms: 1.01x slower                                                  |
| python_startup_no_site   | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                                 |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                                  |
| sqlite_synth             | 1.68 us                                                     | 1.72 us: 1.02x slower                                                 |
| gc_traversal             | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                                 |
| float                    | 54.6 ms                                                     | 55.9 ms: 1.02x slower                                                 |
| create_gc_cycles         | 693 us                                                      | 714 us: 1.03x slower                                                  |
| dulwich_log              | 44.5 ms                                                     | 45.9 ms: 1.03x slower                                                 |
| bench_thread_pool        | 852 us                                                      | 883 us: 1.04x slower                                                  |
| richards_super           | 37.5 ms                                                     | 39.0 ms: 1.04x slower                                                 |
| python_startup           | 18.7 ms                                                     | 19.5 ms: 1.05x slower                                                 |
| nqueens                  | 64.9 ms                                                     | 67.8 ms: 1.05x slower                                                 |
| json_loads               | 12.9 us                                                     | 13.5 us: 1.05x slower                                                 |
| unpack_sequence          | 46.1 ns                                                     | 48.2 ns: 1.05x slower                                                 |
| sqlglot_parse            | 952 us                                                      | 999 us: 1.05x slower                                                  |
| coverage                 | 55.9 ms                                                     | 58.7 ms: 1.05x slower                                                 |
| sqlglot_transpile        | 1.16 ms                                                     | 1.23 ms: 1.05x slower                                                 |
| bench_mp_pool            | 62.5 ms                                                     | 66.0 ms: 1.06x slower                                                 |
| tomli_loads              | 1.41 sec                                                    | 1.50 sec: 1.06x slower                                                |
| comprehensions           | 15.9 us                                                     | 16.9 us: 1.06x slower                                                 |
| unpickle_list            | 2.55 us                                                     | 2.71 us: 1.06x slower                                                 |
| docutils                 | 1.60 sec                                                    | 1.71 sec: 1.07x slower                                                |
| crypto_pyaes             | 47.6 ms                                                     | 50.7 ms: 1.07x slower                                                 |
| regex_dna                | 115 ms                                                      | 123 ms: 1.07x slower                                                  |
| pickle_list              | 2.68 us                                                     | 2.86 us: 1.07x slower                                                 |
| chaos                    | 47.1 ms                                                     | 50.4 ms: 1.07x slower                                                 |
| logging_simple           | 6.61 us                                                     | 7.10 us: 1.07x slower                                                 |
| meteor_contest           | 74.7 ms                                                     | 80.4 ms: 1.08x slower                                                 |
| logging_format           | 7.01 us                                                     | 7.56 us: 1.08x slower                                                 |
| regex_effbot             | 1.50 ms                                                     | 1.63 ms: 1.09x slower                                                 |
| xml_etree_iterparse      | 62.6 ms                                                     | 68.0 ms: 1.09x slower                                                 |
| fannkuch                 | 252 ms                                                      | 277 ms: 1.10x slower                                                  |
| sqlglot_normalize        | 190 ms                                                      | 209 ms: 1.10x slower                                                  |
| regex_compile            | 90.6 ms                                                     | 100 ms: 1.10x slower                                                  |
| pathlib                  | 71.4 ms                                                     | 79.0 ms: 1.11x slower                                                 |
| deltablue                | 2.61 ms                                                     | 2.90 ms: 1.11x slower                                                 |
| deepcopy                 | 246 us                                                      | 273 us: 1.11x slower                                                  |
| pickle_pure_python       | 200 us                                                      | 224 us: 1.12x slower                                                  |
| sqlglot_optimize         | 34.9 ms                                                     | 39.2 ms: 1.12x slower                                                 |
| unpickle_pure_python     | 152 us                                                      | 171 us: 1.12x slower                                                  |
| pickle                   | 6.61 us                                                     | 7.44 us: 1.13x slower                                                 |
| pycparser                | 691 ms                                                      | 781 ms: 1.13x slower                                                  |
| hexiom                   | 4.55 ms                                                     | 5.18 ms: 1.14x slower                                                 |
| scimark_fft              | 178 ms                                                      | 203 ms: 1.14x slower                                                  |
| pyflate                  | 304 ms                                                      | 348 ms: 1.14x slower                                                  |
| regex_v8                 | 13.8 ms                                                     | 15.9 ms: 1.15x slower                                                 |
| scimark_monte_carlo      | 44.6 ms                                                     | 51.6 ms: 1.15x slower                                                 |
| richards                 | 30.6 ms                                                     | 35.5 ms: 1.16x slower                                                 |
| deepcopy_reduce          | 2.07 us                                                     | 2.41 us: 1.16x slower                                                 |
| pprint_safe_repr         | 512 ms                                                      | 596 ms: 1.17x slower                                                  |
| go                       | 97.3 ms                                                     | 114 ms: 1.17x slower                                                  |
| pprint_pformat           | 1.04 sec                                                    | 1.22 sec: 1.18x slower                                                |
| scimark_lu               | 63.5 ms                                                     | 74.9 ms: 1.18x slower                                                 |
| spectral_norm            | 67.9 ms                                                     | 80.6 ms: 1.19x slower                                                 |
| xml_etree_generate       | 52.2 ms                                                     | 62.7 ms: 1.20x slower                                                 |
| xml_etree_process        | 37.1 ms                                                     | 44.9 ms: 1.21x slower                                                 |
| telco                    | 3.90 ms                                                     | 4.86 ms: 1.24x slower                                                 |
| nbody                    | 70.0 ms                                                     | 88.2 ms: 1.26x slower                                                 |
| deepcopy_memo            | 25.2 us                                                     | 31.8 us: 1.26x slower                                                 |
| coroutines               | 14.6 ms                                                     | 18.9 ms: 1.29x slower                                                 |
| logging_silent           | 69.8 ns                                                     | 93.0 ns: 1.33x slower                                                 |
| scimark_sor              | 75.6 ms                                                     | 105 ms: 1.39x slower                                                  |
| async_generators         | 178 ms                                                      | 273 ms: 1.54x slower                                                  |
| Geometric mean           | (ref)                                                       | 1.06x slower                                                          |

Benchmark hidden because not significant (5): pickle_dict, async_tree_memoization, unpickle, tornado_http, generators
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
