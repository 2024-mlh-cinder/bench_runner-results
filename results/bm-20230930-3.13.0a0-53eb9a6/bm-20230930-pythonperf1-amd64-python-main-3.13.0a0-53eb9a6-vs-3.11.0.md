
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.05x faster
- HPT reliability: 99.16%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| tornado_http   | 91.8 ms                                                     | 88.4 ms: 1.04x faster                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                               |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                       |
| nbody          | 70.0 ms                                                     | 72.5 ms: 1.04x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 89.1 ms: 1.02x faster                                      |
| regex_dna      | 115 ms                                                      | 120 ms: 1.04x slower                                       |
| regex_effbot   | 1.50 ms                                                     | 1.60 ms: 1.07x slower                                      |
| regex_v8       | 13.8 ms                                                     | 15.7 ms: 1.14x slower                                      |
| Geometric mean | (ref)                                                       | 1.06x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.76 ms: 1.31x faster                                      |
| unpickle_pure_python | 152 us                                                      | 134 us: 1.13x faster                                       |
| pickle_pure_python   | 200 us                                                      | 190 us: 1.05x faster                                       |
| xml_etree_parse      | 95.9 ms                                                     | 91.8 ms: 1.04x faster                                      |
| xml_etree_iterparse  | 62.6 ms                                                     | 64.1 ms: 1.02x slower                                      |
| xml_etree_process    | 37.1 ms                                                     | 38.2 ms: 1.03x slower                                      |
| unpickle_list        | 2.55 us                                                     | 2.63 us: 1.03x slower                                      |
| unpickle             | 8.09 us                                                     | 8.40 us: 1.04x slower                                      |
| tomli_loads          | 1.41 sec                                                    | 1.48 sec: 1.04x slower                                     |
| json_loads           | 12.9 us                                                     | 13.7 us: 1.06x slower                                      |
| xml_etree_generate   | 52.2 ms                                                     | 55.5 ms: 1.06x slower                                      |
| pickle               | 6.61 us                                                     | 7.10 us: 1.07x slower                                      |
| pickle_list          | 2.68 us                                                     | 3.21 us: 1.20x slower                                      |
| Geometric mean       | (ref)                                                       | 1.00x slower                                               |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.3 ms: 1.03x slower                                      |
| python_startup         | 18.7 ms                                                     | 19.6 ms: 1.05x slower                                      |
| Geometric mean         | (ref)                                                       | 1.04x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.33 ms: 1.01x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 93.7 us: 3.43x faster                                      |
| asyncio_tcp              | 699 ms                                                      | 470 ms: 1.49x faster                                       |
| generators               | 33.8 ms                                                     | 23.2 ms: 1.45x faster                                      |
| json_dumps               | 7.56 ms                                                     | 5.76 ms: 1.31x faster                                      |
| raytrace                 | 211 ms                                                      | 174 ms: 1.21x faster                                       |
| deltablue                | 2.61 ms                                                     | 2.19 ms: 1.19x faster                                      |
| unpack_sequence          | 46.1 ns                                                     | 38.6 ns: 1.19x faster                                      |
| coverage                 | 55.9 ms                                                     | 46.9 ms: 1.19x faster                                      |
| async_tree_none          | 320 ms                                                      | 269 ms: 1.19x faster                                       |
| richards_super           | 37.5 ms                                                     | 31.7 ms: 1.18x faster                                      |
| sqlglot_parse            | 952 us                                                      | 810 us: 1.17x faster                                       |
| chaos                    | 47.1 ms                                                     | 40.4 ms: 1.17x faster                                      |
| mdp                      | 1.67 sec                                                    | 1.46 sec: 1.15x faster                                     |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.86 sec: 1.13x faster                                     |
| unpickle_pure_python     | 152 us                                                      | 134 us: 1.13x faster                                       |
| comprehensions           | 15.9 us                                                     | 14.1 us: 1.13x faster                                      |
| sqlglot_transpile        | 1.16 ms                                                     | 1.03 ms: 1.13x faster                                      |
| json                     | 3.25 ms                                                     | 2.90 ms: 1.12x faster                                      |
| hexiom                   | 4.55 ms                                                     | 4.13 ms: 1.10x faster                                      |
| logging_silent           | 69.8 ns                                                     | 63.5 ns: 1.10x faster                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 40.6 ms: 1.10x faster                                      |
| scimark_lu               | 63.5 ms                                                     | 58.0 ms: 1.10x faster                                      |
| go                       | 97.3 ms                                                     | 89.5 ms: 1.09x faster                                      |
| async_tree_memoization   | 371 ms                                                      | 344 ms: 1.08x faster                                       |
| nqueens                  | 64.9 ms                                                     | 60.2 ms: 1.08x faster                                      |
| async_tree_io            | 779 ms                                                      | 723 ms: 1.08x faster                                       |
| richards                 | 30.6 ms                                                     | 28.4 ms: 1.08x faster                                      |
| mypy2                    | 229 ms                                                      | 213 ms: 1.08x faster                                       |
| spectral_norm            | 67.9 ms                                                     | 63.3 ms: 1.07x faster                                      |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 471 ms: 1.06x faster                                       |
| deepcopy                 | 246 us                                                      | 231 us: 1.06x faster                                       |
| crypto_pyaes             | 47.6 ms                                                     | 45.0 ms: 1.06x faster                                      |
| deepcopy_memo            | 25.2 us                                                     | 23.9 us: 1.05x faster                                      |
| pickle_pure_python       | 200 us                                                      | 190 us: 1.05x faster                                       |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.45 ms: 1.05x faster                                      |
| xml_etree_parse          | 95.9 ms                                                     | 91.8 ms: 1.04x faster                                      |
| sqlglot_normalize        | 190 ms                                                      | 183 ms: 1.04x faster                                       |
| tornado_http             | 91.8 ms                                                     | 88.4 ms: 1.04x faster                                      |
| logging_simple           | 6.61 us                                                     | 6.44 us: 1.03x faster                                      |
| logging_format           | 7.01 us                                                     | 6.85 us: 1.02x faster                                      |
| fannkuch                 | 252 ms                                                      | 246 ms: 1.02x faster                                       |
| scimark_fft              | 178 ms                                                      | 175 ms: 1.02x faster                                       |
| meteor_contest           | 74.7 ms                                                     | 73.4 ms: 1.02x faster                                      |
| regex_compile            | 90.6 ms                                                     | 89.1 ms: 1.02x faster                                      |
| pyflate                  | 304 ms                                                      | 299 ms: 1.02x faster                                       |
| sqlglot_optimize         | 34.9 ms                                                     | 34.7 ms: 1.01x faster                                      |
| mako                     | 7.26 ms                                                     | 7.33 ms: 1.01x slower                                      |
| dulwich_log              | 44.5 ms                                                     | 44.9 ms: 1.01x slower                                      |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                       |
| pprint_safe_repr         | 512 ms                                                      | 519 ms: 1.01x slower                                       |
| scimark_sor              | 75.6 ms                                                     | 76.8 ms: 1.02x slower                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                     |
| xml_etree_iterparse      | 62.6 ms                                                     | 64.1 ms: 1.02x slower                                      |
| python_startup_no_site   | 15.9 ms                                                     | 16.3 ms: 1.03x slower                                      |
| xml_etree_process        | 37.1 ms                                                     | 38.2 ms: 1.03x slower                                      |
| unpickle_list            | 2.55 us                                                     | 2.63 us: 1.03x slower                                      |
| nbody                    | 70.0 ms                                                     | 72.5 ms: 1.04x slower                                      |
| sqlite_synth             | 1.68 us                                                     | 1.75 us: 1.04x slower                                      |
| unpickle                 | 8.09 us                                                     | 8.40 us: 1.04x slower                                      |
| gc_traversal             | 1.46 ms                                                     | 1.51 ms: 1.04x slower                                      |
| regex_dna                | 115 ms                                                      | 120 ms: 1.04x slower                                       |
| tomli_loads              | 1.41 sec                                                    | 1.48 sec: 1.04x slower                                     |
| python_startup           | 18.7 ms                                                     | 19.6 ms: 1.05x slower                                      |
| json_loads               | 12.9 us                                                     | 13.7 us: 1.06x slower                                      |
| create_gc_cycles         | 693 us                                                      | 734 us: 1.06x slower                                       |
| xml_etree_generate       | 52.2 ms                                                     | 55.5 ms: 1.06x slower                                      |
| regex_effbot             | 1.50 ms                                                     | 1.60 ms: 1.07x slower                                      |
| pickle                   | 6.61 us                                                     | 7.10 us: 1.07x slower                                      |
| bench_mp_pool            | 62.5 ms                                                     | 68.6 ms: 1.10x slower                                      |
| pathlib                  | 71.4 ms                                                     | 78.7 ms: 1.10x slower                                      |
| pycparser                | 691 ms                                                      | 775 ms: 1.12x slower                                       |
| regex_v8                 | 13.8 ms                                                     | 15.7 ms: 1.14x slower                                      |
| pickle_list              | 2.68 us                                                     | 3.21 us: 1.20x slower                                      |
| telco                    | 3.90 ms                                                     | 4.91 ms: 1.26x slower                                      |
| async_generators         | 178 ms                                                      | 236 ms: 1.33x slower                                       |
| Geometric mean           | (ref)                                                       | 1.05x faster                                               |

Benchmark hidden because not significant (6): bench_thread_pool, pickle_dict, float, deepcopy_reduce, docutils, coroutines
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.16% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
