
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_opargs
- machine: windows-amd64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.00x slower
- HPT reliability: 99.56%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                                    |
| Geometric mean | (ref)                                                       | 1.03x slower                                                              |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                                      |
| float          | 54.6 ms                                                     | 56.9 ms: 1.04x slower                                                     |
| nbody          | 70.0 ms                                                     | 76.3 ms: 1.09x slower                                                     |
| Geometric mean | (ref)                                                       | 1.05x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 118 ms: 1.02x slower                                                      |
| regex_effbot   | 1.50 ms                                                     | 1.56 ms: 1.05x slower                                                     |
| regex_compile  | 90.6 ms                                                     | 96.1 ms: 1.06x slower                                                     |
| regex_v8       | 13.8 ms                                                     | 15.1 ms: 1.09x slower                                                     |
| Geometric mean | (ref)                                                       | 1.05x slower                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.84 ms: 1.29x faster                                                     |
| xml_etree_parse      | 95.9 ms                                                     | 91.6 ms: 1.05x faster                                                     |
| unpickle_pure_python | 152 us                                                      | 146 us: 1.04x faster                                                      |
| pickle_dict          | 18.5 us                                                     | 18.1 us: 1.02x faster                                                     |
| xml_etree_iterparse  | 62.6 ms                                                     | 65.6 ms: 1.05x slower                                                     |
| tomli_loads          | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                                    |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                                     |
| unpickle             | 8.09 us                                                     | 8.53 us: 1.05x slower                                                     |
| pickle               | 6.61 us                                                     | 7.12 us: 1.08x slower                                                     |
| xml_etree_process    | 37.1 ms                                                     | 40.0 ms: 1.08x slower                                                     |
| unpickle_list        | 2.55 us                                                     | 2.76 us: 1.08x slower                                                     |
| pickle_list          | 2.68 us                                                     | 2.91 us: 1.09x slower                                                     |
| xml_etree_generate   | 52.2 ms                                                     | 57.6 ms: 1.10x slower                                                     |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                              |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.7 ms: 1.05x slower                                                     |
| python_startup         | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                                     |
| Geometric mean         | (ref)                                                       | 1.06x slower                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.81 ms: 1.07x faster                                                     |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 99.9 us: 3.22x faster                                                     |
| asyncio_tcp              | 699 ms                                                      | 478 ms: 1.46x faster                                                      |
| generators               | 33.8 ms                                                     | 25.1 ms: 1.35x faster                                                     |
| json_dumps               | 7.56 ms                                                     | 5.84 ms: 1.29x faster                                                     |
| coverage                 | 55.9 ms                                                     | 46.4 ms: 1.20x faster                                                     |
| async_tree_none          | 320 ms                                                      | 283 ms: 1.13x faster                                                      |
| deltablue                | 2.61 ms                                                     | 2.34 ms: 1.12x faster                                                     |
| json                     | 3.25 ms                                                     | 2.92 ms: 1.12x faster                                                     |
| raytrace                 | 211 ms                                                      | 191 ms: 1.10x faster                                                      |
| mdp                      | 1.67 sec                                                    | 1.55 sec: 1.08x faster                                                    |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.97 sec: 1.07x faster                                                    |
| logging_silent           | 69.8 ns                                                     | 65.4 ns: 1.07x faster                                                     |
| richards_super           | 37.5 ms                                                     | 35.1 ms: 1.07x faster                                                     |
| mako                     | 7.26 ms                                                     | 6.81 ms: 1.07x faster                                                     |
| sqlglot_parse            | 952 us                                                      | 896 us: 1.06x faster                                                      |
| xml_etree_parse          | 95.9 ms                                                     | 91.6 ms: 1.05x faster                                                     |
| async_tree_io            | 779 ms                                                      | 749 ms: 1.04x faster                                                      |
| unpickle_pure_python     | 152 us                                                      | 146 us: 1.04x faster                                                      |
| sqlglot_transpile        | 1.16 ms                                                     | 1.13 ms: 1.03x faster                                                     |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 490 ms: 1.02x faster                                                      |
| pickle_dict              | 18.5 us                                                     | 18.1 us: 1.02x faster                                                     |
| chaos                    | 47.1 ms                                                     | 46.1 ms: 1.02x faster                                                     |
| async_tree_memoization   | 371 ms                                                      | 363 ms: 1.02x faster                                                      |
| comprehensions           | 15.9 us                                                     | 15.7 us: 1.02x faster                                                     |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.55 ms: 1.01x faster                                                     |
| bench_thread_pool        | 852 us                                                      | 860 us: 1.01x slower                                                      |
| spectral_norm            | 67.9 ms                                                     | 68.7 ms: 1.01x slower                                                     |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                                      |
| crypto_pyaes             | 47.6 ms                                                     | 48.5 ms: 1.02x slower                                                     |
| regex_dna                | 115 ms                                                      | 118 ms: 1.02x slower                                                      |
| deepcopy                 | 246 us                                                      | 253 us: 1.03x slower                                                      |
| gc_traversal             | 1.46 ms                                                     | 1.51 ms: 1.03x slower                                                     |
| nqueens                  | 64.9 ms                                                     | 67.0 ms: 1.03x slower                                                     |
| coroutines               | 14.6 ms                                                     | 15.1 ms: 1.03x slower                                                     |
| logging_simple           | 6.61 us                                                     | 6.87 us: 1.04x slower                                                     |
| float                    | 54.6 ms                                                     | 56.9 ms: 1.04x slower                                                     |
| create_gc_cycles         | 693 us                                                      | 722 us: 1.04x slower                                                      |
| pyflate                  | 304 ms                                                      | 318 ms: 1.05x slower                                                      |
| regex_effbot             | 1.50 ms                                                     | 1.56 ms: 1.05x slower                                                     |
| sqlite_synth             | 1.68 us                                                     | 1.76 us: 1.05x slower                                                     |
| logging_format           | 7.01 us                                                     | 7.35 us: 1.05x slower                                                     |
| hexiom                   | 4.55 ms                                                     | 4.77 ms: 1.05x slower                                                     |
| xml_etree_iterparse      | 62.6 ms                                                     | 65.6 ms: 1.05x slower                                                     |
| tomli_loads              | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                                    |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                                     |
| unpickle                 | 8.09 us                                                     | 8.53 us: 1.05x slower                                                     |
| python_startup_no_site   | 15.9 ms                                                     | 16.7 ms: 1.05x slower                                                     |
| dulwich_log              | 44.5 ms                                                     | 47.0 ms: 1.06x slower                                                     |
| unpack_sequence          | 46.1 ns                                                     | 48.8 ns: 1.06x slower                                                     |
| pprint_safe_repr         | 512 ms                                                      | 542 ms: 1.06x slower                                                      |
| python_startup           | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                                     |
| docutils                 | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                                    |
| regex_compile            | 90.6 ms                                                     | 96.1 ms: 1.06x slower                                                     |
| meteor_contest           | 74.7 ms                                                     | 79.7 ms: 1.07x slower                                                     |
| go                       | 97.3 ms                                                     | 104 ms: 1.07x slower                                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.12 sec: 1.07x slower                                                    |
| deepcopy_reduce          | 2.07 us                                                     | 2.23 us: 1.07x slower                                                     |
| pickle                   | 6.61 us                                                     | 7.12 us: 1.08x slower                                                     |
| sqlglot_normalize        | 190 ms                                                      | 205 ms: 1.08x slower                                                      |
| xml_etree_process        | 37.1 ms                                                     | 40.0 ms: 1.08x slower                                                     |
| unpickle_list            | 2.55 us                                                     | 2.76 us: 1.08x slower                                                     |
| pickle_list              | 2.68 us                                                     | 2.91 us: 1.09x slower                                                     |
| pycparser                | 691 ms                                                      | 752 ms: 1.09x slower                                                      |
| nbody                    | 70.0 ms                                                     | 76.3 ms: 1.09x slower                                                     |
| scimark_fft              | 178 ms                                                      | 194 ms: 1.09x slower                                                      |
| regex_v8                 | 13.8 ms                                                     | 15.1 ms: 1.09x slower                                                     |
| sqlglot_optimize         | 34.9 ms                                                     | 38.1 ms: 1.09x slower                                                     |
| xml_etree_generate       | 52.2 ms                                                     | 57.6 ms: 1.10x slower                                                     |
| pathlib                  | 71.4 ms                                                     | 79.3 ms: 1.11x slower                                                     |
| bench_mp_pool            | 62.5 ms                                                     | 71.1 ms: 1.14x slower                                                     |
| scimark_sor              | 75.6 ms                                                     | 86.1 ms: 1.14x slower                                                     |
| telco                    | 3.90 ms                                                     | 4.63 ms: 1.19x slower                                                     |
| async_generators         | 178 ms                                                      | 253 ms: 1.42x slower                                                      |
| dask                     | 264 ms                                                      | 396 ms: 1.50x slower                                                      |
| Geometric mean           | (ref)                                                       | 1.00x slower                                                              |

Benchmark hidden because not significant (8): pickle_pure_python, deepcopy_memo, tornado_http, richards, scimark_lu, scimark_monte_carlo, mypy2, fannkuch
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.56% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
