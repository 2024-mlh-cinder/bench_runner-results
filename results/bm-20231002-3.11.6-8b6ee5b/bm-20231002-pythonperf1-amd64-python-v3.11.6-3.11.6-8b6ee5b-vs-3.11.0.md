
# Results vs. 3.11.0

- fork: python
- ref: v3.11.6
- machine: windows-amd64
- commit hash: 8b6ee5b
- commit date: 2023-10-02
- overall geometric mean: 1.01x slower
- HPT reliability: 95.23%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 207 ms: 1.01x faster                                        |
| chameleon      | 5.11 ms                                                     | 5.24 ms: 1.02x slower                                       |
| html5lib       | 37.5 ms                                                     | 38.9 ms: 1.04x slower                                       |
| tornado_http   | 91.8 ms                                                     | 90.5 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

Benchmark hidden because not significant (3): float, nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 91.7 ms: 1.01x slower                                       |
| regex_effbot   | 1.50 ms                                                     | 1.53 ms: 1.02x slower                                       |
| regex_v8       | 13.8 ms                                                     | 14.2 ms: 1.02x slower                                       |
| regex_dna      | 115 ms                                                      | 122 ms: 1.06x slower                                        |
| Geometric mean | (ref)                                                       | 1.03x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|---------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle            | 8.09 us                                                     | 7.67 us: 1.06x faster                                       |
| pickle_list         | 2.68 us                                                     | 2.70 us: 1.01x slower                                       |
| xml_etree_iterparse | 62.6 ms                                                     | 63.3 ms: 1.01x slower                                       |
| xml_etree_generate  | 52.2 ms                                                     | 52.9 ms: 1.01x slower                                       |
| xml_etree_parse     | 95.9 ms                                                     | 97.3 ms: 1.01x slower                                       |
| pickle_pure_python  | 200 us                                                      | 203 us: 1.02x slower                                        |
| xml_etree_process   | 37.1 ms                                                     | 37.8 ms: 1.02x slower                                       |
| json_loads          | 12.9 us                                                     | 13.2 us: 1.02x slower                                       |
| json_dumps          | 7.56 ms                                                     | 7.74 ms: 1.02x slower                                       |
| unpickle_list       | 2.55 us                                                     | 2.64 us: 1.04x slower                                       |
| Geometric mean      | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (4): unpickle_pure_python, pickle_dict, tomli_loads, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.6 ms: 1.02x faster                                       |
| Geometric mean         | (ref)                                                       | 1.01x faster                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| django_template | 24.1 ms                                                     | 23.6 ms: 1.02x faster                                       |
| genshi_text     | 17.0 ms                                                     | 17.2 ms: 1.01x slower                                       |
| genshi_xml      | 37.3 ms                                                     | 38.1 ms: 1.02x slower                                       |
| Geometric mean  | (ref)                                                       | 1.00x slower                                                |

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| bench_mp_pool            | 62.5 ms                                                     | 58.7 ms: 1.06x faster                                       |
| unpickle                 | 8.09 us                                                     | 7.67 us: 1.06x faster                                       |
| aiohttp                  | 899 us                                                      | 853 us: 1.05x faster                                        |
| fannkuch                 | 252 ms                                                      | 241 ms: 1.05x faster                                        |
| coverage                 | 55.9 ms                                                     | 53.6 ms: 1.04x faster                                       |
| pathlib                  | 71.4 ms                                                     | 68.5 ms: 1.04x faster                                       |
| raytrace                 | 211 ms                                                      | 203 ms: 1.04x faster                                        |
| async_tree_none          | 320 ms                                                      | 311 ms: 1.03x faster                                        |
| scimark_lu               | 63.5 ms                                                     | 61.9 ms: 1.03x faster                                       |
| pylint                   | 326 ms                                                      | 318 ms: 1.03x faster                                        |
| django_template          | 24.1 ms                                                     | 23.6 ms: 1.02x faster                                       |
| sqlglot_transpile        | 1.16 ms                                                     | 1.14 ms: 1.02x faster                                       |
| python_startup_no_site   | 15.9 ms                                                     | 15.6 ms: 1.02x faster                                       |
| nqueens                  | 64.9 ms                                                     | 63.7 ms: 1.02x faster                                       |
| tornado_http             | 91.8 ms                                                     | 90.5 ms: 1.01x faster                                       |
| sqlglot_parse            | 952 us                                                      | 938 us: 1.01x faster                                        |
| comprehensions           | 15.9 us                                                     | 15.7 us: 1.01x faster                                       |
| thrift                   | 491 us                                                      | 487 us: 1.01x faster                                        |
| 2to3                     | 209 ms                                                      | 207 ms: 1.01x faster                                        |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.55 ms: 1.01x faster                                       |
| spectral_norm            | 67.9 ms                                                     | 67.5 ms: 1.01x faster                                       |
| flaskblogging            | 2.04 sec                                                    | 2.03 sec: 1.01x faster                                      |
| sqlglot_optimize         | 34.9 ms                                                     | 35.1 ms: 1.01x slower                                       |
| telco                    | 3.90 ms                                                     | 3.93 ms: 1.01x slower                                       |
| deltablue                | 2.61 ms                                                     | 2.63 ms: 1.01x slower                                       |
| async_generators         | 178 ms                                                      | 179 ms: 1.01x slower                                        |
| sqlalchemy_imperative    | 10.2 ms                                                     | 10.3 ms: 1.01x slower                                       |
| pickle_list              | 2.68 us                                                     | 2.70 us: 1.01x slower                                       |
| typing_runtime_protocols | 322 us                                                      | 324 us: 1.01x slower                                        |
| sqlglot_normalize        | 190 ms                                                      | 192 ms: 1.01x slower                                        |
| pprint_safe_repr         | 512 ms                                                      | 517 ms: 1.01x slower                                        |
| dulwich_log              | 44.5 ms                                                     | 45.0 ms: 1.01x slower                                       |
| deepcopy_reduce          | 2.07 us                                                     | 2.10 us: 1.01x slower                                       |
| genshi_text              | 17.0 ms                                                     | 17.2 ms: 1.01x slower                                       |
| logging_silent           | 69.8 ns                                                     | 70.7 ns: 1.01x slower                                       |
| regex_compile            | 90.6 ms                                                     | 91.7 ms: 1.01x slower                                       |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.3 ms: 1.01x slower                                       |
| xml_etree_generate       | 52.2 ms                                                     | 52.9 ms: 1.01x slower                                       |
| xml_etree_parse          | 95.9 ms                                                     | 97.3 ms: 1.01x slower                                       |
| scimark_fft              | 178 ms                                                      | 181 ms: 1.01x slower                                        |
| pickle_pure_python       | 200 us                                                      | 203 us: 1.02x slower                                        |
| logging_simple           | 6.61 us                                                     | 6.72 us: 1.02x slower                                       |
| gc_traversal             | 1.46 ms                                                     | 1.48 ms: 1.02x slower                                       |
| scimark_sor              | 75.6 ms                                                     | 76.8 ms: 1.02x slower                                       |
| meteor_contest           | 74.7 ms                                                     | 76.1 ms: 1.02x slower                                       |
| xml_etree_process        | 37.1 ms                                                     | 37.8 ms: 1.02x slower                                       |
| sympy_sum                | 99.9 ms                                                     | 102 ms: 1.02x slower                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                      |
| genshi_xml               | 37.3 ms                                                     | 38.1 ms: 1.02x slower                                       |
| json_loads               | 12.9 us                                                     | 13.2 us: 1.02x slower                                       |
| create_gc_cycles         | 693 us                                                      | 708 us: 1.02x slower                                        |
| regex_effbot             | 1.50 ms                                                     | 1.53 ms: 1.02x slower                                       |
| sqlite_synth             | 1.68 us                                                     | 1.72 us: 1.02x slower                                       |
| richards_super           | 37.5 ms                                                     | 38.4 ms: 1.02x slower                                       |
| logging_format           | 7.01 us                                                     | 7.18 us: 1.02x slower                                       |
| json_dumps               | 7.56 ms                                                     | 7.74 ms: 1.02x slower                                       |
| chameleon                | 5.11 ms                                                     | 5.24 ms: 1.02x slower                                       |
| regex_v8                 | 13.8 ms                                                     | 14.2 ms: 1.02x slower                                       |
| mdp                      | 1.67 sec                                                    | 1.71 sec: 1.03x slower                                      |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 515 ms: 1.03x slower                                        |
| sqlalchemy_declarative   | 81.5 ms                                                     | 83.8 ms: 1.03x slower                                       |
| sympy_str                | 182 ms                                                      | 187 ms: 1.03x slower                                        |
| sympy_expand             | 295 ms                                                      | 305 ms: 1.04x slower                                        |
| crypto_pyaes             | 47.6 ms                                                     | 49.3 ms: 1.04x slower                                       |
| html5lib                 | 37.5 ms                                                     | 38.9 ms: 1.04x slower                                       |
| scimark_monte_carlo      | 44.6 ms                                                     | 46.3 ms: 1.04x slower                                       |
| unpickle_list            | 2.55 us                                                     | 2.64 us: 1.04x slower                                       |
| asyncio_tcp              | 699 ms                                                      | 728 ms: 1.04x slower                                        |
| go                       | 97.3 ms                                                     | 102 ms: 1.05x slower                                        |
| chaos                    | 47.1 ms                                                     | 49.7 ms: 1.06x slower                                       |
| regex_dna                | 115 ms                                                      | 122 ms: 1.06x slower                                        |
| mypy2                    | 229 ms                                                      | 277 ms: 1.21x slower                                        |
| Geometric mean           | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (26): json, asyncio_tcp_ssl, python_startup, float, dask, unpickle_pure_python, nbody, pickle_dict, hexiom, generators, bench_thread_pool, async_tree_io, tomli_loads, sympy_integrate, pidigits, docutils, deepcopy, richards, pyflate, coroutines, deepcopy_memo, pycparser, unpack_sequence, mako, pickle, async_tree_memoization


# HPT report

- Reliability score: 95.23% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
