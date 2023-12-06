
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_pic
- machine: windows-amd64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.00x faster
- HPT reliability: 99.12%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.67 sec: 1.04x slower                                                    |
| tornado_http   | 91.8 ms                                                     | 89.3 ms: 1.03x faster                                                     |
| Geometric mean | (ref)                                                       | 1.01x slower                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                                      |
| float          | 54.6 ms                                                     | 56.2 ms: 1.03x slower                                                     |
| nbody          | 70.0 ms                                                     | 77.1 ms: 1.10x slower                                                     |
| Geometric mean | (ref)                                                       | 1.05x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 94.7 ms: 1.04x slower                                                     |
| regex_dna      | 115 ms                                                      | 123 ms: 1.07x slower                                                      |
| regex_v8       | 13.8 ms                                                     | 15.2 ms: 1.10x slower                                                     |
| regex_effbot   | 1.50 ms                                                     | 1.64 ms: 1.10x slower                                                     |
| Geometric mean | (ref)                                                       | 1.08x slower                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|---------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| json_dumps          | 7.56 ms                                                     | 5.82 ms: 1.30x faster                                                     |
| xml_etree_parse     | 95.9 ms                                                     | 91.4 ms: 1.05x faster                                                     |
| pickle_pure_python  | 200 us                                                      | 203 us: 1.01x slower                                                      |
| pickle_dict         | 18.5 us                                                     | 18.9 us: 1.02x slower                                                     |
| xml_etree_iterparse | 62.6 ms                                                     | 65.3 ms: 1.04x slower                                                     |
| unpickle            | 8.09 us                                                     | 8.46 us: 1.05x slower                                                     |
| json_loads          | 12.9 us                                                     | 13.5 us: 1.05x slower                                                     |
| tomli_loads         | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                                    |
| unpickle_list       | 2.55 us                                                     | 2.70 us: 1.06x slower                                                     |
| xml_etree_process   | 37.1 ms                                                     | 39.9 ms: 1.08x slower                                                     |
| pickle_list         | 2.68 us                                                     | 2.93 us: 1.09x slower                                                     |
| xml_etree_generate  | 52.2 ms                                                     | 58.2 ms: 1.11x slower                                                     |
| pickle              | 6.61 us                                                     | 7.38 us: 1.12x slower                                                     |
| Geometric mean      | (ref)                                                       | 1.03x slower                                                              |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                                     |
| python_startup         | 18.7 ms                                                     | 19.1 ms: 1.02x slower                                                     |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.74 ms: 1.08x faster                                                     |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 98.9 us: 3.25x faster                                                     |
| asyncio_tcp              | 699 ms                                                      | 479 ms: 1.46x faster                                                      |
| generators               | 33.8 ms                                                     | 24.1 ms: 1.40x faster                                                     |
| json_dumps               | 7.56 ms                                                     | 5.82 ms: 1.30x faster                                                     |
| coverage                 | 55.9 ms                                                     | 46.6 ms: 1.20x faster                                                     |
| async_tree_none          | 320 ms                                                      | 273 ms: 1.17x faster                                                      |
| raytrace                 | 211 ms                                                      | 183 ms: 1.15x faster                                                      |
| deltablue                | 2.61 ms                                                     | 2.31 ms: 1.13x faster                                                     |
| json                     | 3.25 ms                                                     | 2.92 ms: 1.12x faster                                                     |
| sqlglot_parse            | 952 us                                                      | 856 us: 1.11x faster                                                      |
| mdp                      | 1.67 sec                                                    | 1.51 sec: 1.10x faster                                                    |
| logging_silent           | 69.8 ns                                                     | 64.4 ns: 1.08x faster                                                     |
| mako                     | 7.26 ms                                                     | 6.74 ms: 1.08x faster                                                     |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.96 sec: 1.08x faster                                                    |
| richards_super           | 37.5 ms                                                     | 34.9 ms: 1.07x faster                                                     |
| sqlglot_transpile        | 1.16 ms                                                     | 1.08 ms: 1.07x faster                                                     |
| async_tree_io            | 779 ms                                                      | 731 ms: 1.06x faster                                                      |
| async_tree_memoization   | 371 ms                                                      | 353 ms: 1.05x faster                                                      |
| xml_etree_parse          | 95.9 ms                                                     | 91.4 ms: 1.05x faster                                                     |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 478 ms: 1.05x faster                                                      |
| chaos                    | 47.1 ms                                                     | 45.1 ms: 1.05x faster                                                     |
| logging_simple           | 6.61 us                                                     | 6.37 us: 1.04x faster                                                     |
| logging_format           | 7.01 us                                                     | 6.80 us: 1.03x faster                                                     |
| mypy2                    | 229 ms                                                      | 222 ms: 1.03x faster                                                      |
| tornado_http             | 91.8 ms                                                     | 89.3 ms: 1.03x faster                                                     |
| unpack_sequence          | 46.1 ns                                                     | 45.2 ns: 1.02x faster                                                     |
| comprehensions           | 15.9 us                                                     | 15.6 us: 1.02x faster                                                     |
| richards                 | 30.6 ms                                                     | 30.3 ms: 1.01x faster                                                     |
| nqueens                  | 64.9 ms                                                     | 65.3 ms: 1.01x slower                                                     |
| fannkuch                 | 252 ms                                                      | 255 ms: 1.01x slower                                                      |
| crypto_pyaes             | 47.6 ms                                                     | 48.0 ms: 1.01x slower                                                     |
| spectral_norm            | 67.9 ms                                                     | 68.7 ms: 1.01x slower                                                     |
| python_startup_no_site   | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                                     |
| pickle_pure_python       | 200 us                                                      | 203 us: 1.01x slower                                                      |
| scimark_lu               | 63.5 ms                                                     | 64.5 ms: 1.02x slower                                                     |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                                      |
| pickle_dict              | 18.5 us                                                     | 18.9 us: 1.02x slower                                                     |
| python_startup           | 18.7 ms                                                     | 19.1 ms: 1.02x slower                                                     |
| bench_thread_pool        | 852 us                                                      | 869 us: 1.02x slower                                                      |
| dulwich_log              | 44.5 ms                                                     | 45.7 ms: 1.03x slower                                                     |
| float                    | 54.6 ms                                                     | 56.2 ms: 1.03x slower                                                     |
| gc_traversal             | 1.46 ms                                                     | 1.51 ms: 1.03x slower                                                     |
| deepcopy                 | 246 us                                                      | 254 us: 1.04x slower                                                      |
| sqlglot_normalize        | 190 ms                                                      | 197 ms: 1.04x slower                                                      |
| create_gc_cycles         | 693 us                                                      | 720 us: 1.04x slower                                                      |
| pyflate                  | 304 ms                                                      | 316 ms: 1.04x slower                                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 46.5 ms: 1.04x slower                                                     |
| docutils                 | 1.60 sec                                                    | 1.67 sec: 1.04x slower                                                    |
| xml_etree_iterparse      | 62.6 ms                                                     | 65.3 ms: 1.04x slower                                                     |
| regex_compile            | 90.6 ms                                                     | 94.7 ms: 1.04x slower                                                     |
| unpickle                 | 8.09 us                                                     | 8.46 us: 1.05x slower                                                     |
| json_loads               | 12.9 us                                                     | 13.5 us: 1.05x slower                                                     |
| coroutines               | 14.6 ms                                                     | 15.3 ms: 1.05x slower                                                     |
| sqlite_synth             | 1.68 us                                                     | 1.77 us: 1.05x slower                                                     |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.70 ms: 1.05x slower                                                     |
| pycparser                | 691 ms                                                      | 726 ms: 1.05x slower                                                      |
| tomli_loads              | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                                    |
| deepcopy_memo            | 25.2 us                                                     | 26.5 us: 1.05x slower                                                     |
| sqlglot_optimize         | 34.9 ms                                                     | 36.7 ms: 1.05x slower                                                     |
| meteor_contest           | 74.7 ms                                                     | 78.7 ms: 1.05x slower                                                     |
| hexiom                   | 4.55 ms                                                     | 4.80 ms: 1.05x slower                                                     |
| unpickle_list            | 2.55 us                                                     | 2.70 us: 1.06x slower                                                     |
| regex_dna                | 115 ms                                                      | 123 ms: 1.07x slower                                                      |
| go                       | 97.3 ms                                                     | 105 ms: 1.07x slower                                                      |
| xml_etree_process        | 37.1 ms                                                     | 39.9 ms: 1.08x slower                                                     |
| deepcopy_reduce          | 2.07 us                                                     | 2.25 us: 1.08x slower                                                     |
| pprint_safe_repr         | 512 ms                                                      | 555 ms: 1.09x slower                                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.13 sec: 1.09x slower                                                    |
| pickle_list              | 2.68 us                                                     | 2.93 us: 1.09x slower                                                     |
| regex_v8                 | 13.8 ms                                                     | 15.2 ms: 1.10x slower                                                     |
| regex_effbot             | 1.50 ms                                                     | 1.64 ms: 1.10x slower                                                     |
| scimark_fft              | 178 ms                                                      | 196 ms: 1.10x slower                                                      |
| nbody                    | 70.0 ms                                                     | 77.1 ms: 1.10x slower                                                     |
| pathlib                  | 71.4 ms                                                     | 79.2 ms: 1.11x slower                                                     |
| bench_mp_pool            | 62.5 ms                                                     | 69.6 ms: 1.11x slower                                                     |
| xml_etree_generate       | 52.2 ms                                                     | 58.2 ms: 1.11x slower                                                     |
| pickle                   | 6.61 us                                                     | 7.38 us: 1.12x slower                                                     |
| scimark_sor              | 75.6 ms                                                     | 90.4 ms: 1.20x slower                                                     |
| telco                    | 3.90 ms                                                     | 4.76 ms: 1.22x slower                                                     |
| async_generators         | 178 ms                                                      | 252 ms: 1.42x slower                                                      |
| dask                     | 264 ms                                                      | 391 ms: 1.48x slower                                                      |
| Geometric mean           | (ref)                                                       | 1.00x faster                                                              |

Benchmark hidden because not significant (1): unpickle_pure_python
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.12% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
