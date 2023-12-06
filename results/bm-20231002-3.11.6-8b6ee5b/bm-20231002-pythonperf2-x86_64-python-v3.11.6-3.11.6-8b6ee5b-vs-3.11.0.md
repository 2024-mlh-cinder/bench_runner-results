
# Results vs. 3.11.0

- fork: python
- ref: v3.11.6
- machine: linux-x86_64
- commit hash: 8b6ee5b
- commit date: 2023-10-02
- overall geometric mean: 1.00x faster
- HPT reliability: 97.75%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 285 ms: 1.01x faster                                         |
| chameleon      | 7.67 ms                                                      | 7.64 ms: 1.00x faster                                        |
| docutils       | 2.86 sec                                                     | 2.83 sec: 1.01x faster                                       |
| html5lib       | 72.9 ms                                                      | 71.9 ms: 1.01x faster                                        |
| tornado_http   | 122 ms                                                       | 123 ms: 1.01x slower                                         |
| Geometric mean | (ref)                                                        | 1.00x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 74.2 ms                                                      | 76.4 ms: 1.03x slower                                        |
| pidigits       | 251 ms                                                       | 268 ms: 1.07x slower                                         |
| nbody          | 90.7 ms                                                      | 96.9 ms: 1.07x slower                                        |
| Geometric mean | (ref)                                                        | 1.06x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.50 ms                                                      | 3.29 ms: 1.07x faster                                        |
| regex_v8       | 23.9 ms                                                      | 23.2 ms: 1.03x faster                                        |
| regex_dna      | 227 ms                                                       | 220 ms: 1.03x faster                                         |
| regex_compile  | 158 ms                                                       | 157 ms: 1.01x faster                                         |
| Geometric mean | (ref)                                                        | 1.03x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| json_loads           | 28.7 us                                                      | 24.6 us: 1.17x faster                                        |
| pickle_list          | 3.83 us                                                      | 3.77 us: 1.02x faster                                        |
| pickle_pure_python   | 319 us                                                       | 315 us: 1.01x faster                                         |
| xml_etree_process    | 56.5 ms                                                      | 55.8 ms: 1.01x faster                                        |
| unpickle             | 13.4 us                                                      | 13.3 us: 1.01x faster                                        |
| xml_etree_generate   | 80.5 ms                                                      | 79.8 ms: 1.01x faster                                        |
| unpickle_pure_python | 241 us                                                       | 239 us: 1.01x faster                                         |
| json_dumps           | 13.4 ms                                                      | 13.3 ms: 1.01x faster                                        |
| tomli_loads          | 2.26 sec                                                     | 2.28 sec: 1.01x slower                                       |
| xml_etree_iterparse  | 104 ms                                                       | 105 ms: 1.01x slower                                         |
| unpickle_list        | 4.53 us                                                      | 4.69 us: 1.03x slower                                        |
| pickle               | 9.64 us                                                      | 9.99 us: 1.04x slower                                        |
| pickle_dict          | 30.8 us                                                      | 32.1 us: 1.04x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                 |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.8 ms: 1.01x slower                                        |
| python_startup_no_site | 7.76 ms                                                      | 7.81 ms: 1.01x slower                                        |
| Geometric mean         | (ref)                                                        | 1.01x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| genshi_xml     | 58.5 ms                                                      | 56.3 ms: 1.04x faster                                        |
| genshi_text    | 26.1 ms                                                      | 25.4 ms: 1.03x faster                                        |
| mako           | 11.0 ms                                                      | 10.8 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                 |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| json_loads               | 28.7 us                                                      | 24.6 us: 1.17x faster                                        |
| chaos                    | 80.9 ms                                                      | 73.4 ms: 1.10x faster                                        |
| json                     | 5.65 ms                                                      | 5.23 ms: 1.08x faster                                        |
| regex_effbot             | 3.50 ms                                                      | 3.29 ms: 1.07x faster                                        |
| logging_format           | 8.11 us                                                      | 7.66 us: 1.06x faster                                        |
| raytrace                 | 317 ms                                                       | 301 ms: 1.05x faster                                         |
| dulwich_log              | 68.4 ms                                                      | 65.3 ms: 1.05x faster                                        |
| deepcopy                 | 399 us                                                       | 383 us: 1.04x faster                                         |
| sqlglot_normalize        | 126 ms                                                       | 121 ms: 1.04x faster                                         |
| genshi_xml               | 58.5 ms                                                      | 56.3 ms: 1.04x faster                                        |
| pycparser                | 1.32 sec                                                     | 1.28 sec: 1.04x faster                                       |
| deepcopy_memo            | 38.8 us                                                      | 37.5 us: 1.04x faster                                        |
| deepcopy_reduce          | 3.51 us                                                      | 3.39 us: 1.03x faster                                        |
| regex_v8                 | 23.9 ms                                                      | 23.2 ms: 1.03x faster                                        |
| logging_simple           | 7.19 us                                                      | 6.96 us: 1.03x faster                                        |
| regex_dna                | 227 ms                                                       | 220 ms: 1.03x faster                                         |
| generators               | 56.0 ms                                                      | 54.3 ms: 1.03x faster                                        |
| genshi_text              | 26.1 ms                                                      | 25.4 ms: 1.03x faster                                        |
| hexiom                   | 7.13 ms                                                      | 6.97 ms: 1.02x faster                                        |
| meteor_contest           | 131 ms                                                       | 128 ms: 1.02x faster                                         |
| sqlglot_optimize         | 59.8 ms                                                      | 58.6 ms: 1.02x faster                                        |
| mako                     | 11.0 ms                                                      | 10.8 ms: 1.02x faster                                        |
| sqlalchemy_imperative    | 20.1 ms                                                      | 19.7 ms: 1.02x faster                                        |
| pickle_list              | 3.83 us                                                      | 3.77 us: 1.02x faster                                        |
| pyflate                  | 449 ms                                                       | 442 ms: 1.01x faster                                         |
| nqueens                  | 103 ms                                                       | 101 ms: 1.01x faster                                         |
| html5lib                 | 72.9 ms                                                      | 71.9 ms: 1.01x faster                                        |
| pickle_pure_python       | 319 us                                                       | 315 us: 1.01x faster                                         |
| async_tree_memoization   | 630 ms                                                       | 622 ms: 1.01x faster                                         |
| go                       | 164 ms                                                       | 162 ms: 1.01x faster                                         |
| crypto_pyaes             | 83.4 ms                                                      | 82.4 ms: 1.01x faster                                        |
| xml_etree_process        | 56.5 ms                                                      | 55.8 ms: 1.01x faster                                        |
| pprint_safe_repr         | 784 ms                                                       | 775 ms: 1.01x faster                                         |
| unpickle                 | 13.4 us                                                      | 13.3 us: 1.01x faster                                        |
| pprint_pformat           | 1.63 sec                                                     | 1.61 sec: 1.01x faster                                       |
| xml_etree_generate       | 80.5 ms                                                      | 79.8 ms: 1.01x faster                                        |
| telco                    | 6.86 ms                                                      | 6.80 ms: 1.01x faster                                        |
| unpickle_pure_python     | 241 us                                                       | 239 us: 1.01x faster                                         |
| sympy_expand             | 555 ms                                                       | 550 ms: 1.01x faster                                         |
| docutils                 | 2.86 sec                                                     | 2.83 sec: 1.01x faster                                       |
| asyncio_tcp              | 753 ms                                                       | 747 ms: 1.01x faster                                         |
| sympy_str                | 337 ms                                                       | 335 ms: 1.01x faster                                         |
| scimark_lu               | 115 ms                                                       | 114 ms: 1.01x faster                                         |
| 2to3                     | 288 ms                                                       | 285 ms: 1.01x faster                                         |
| typing_runtime_protocols | 523 us                                                       | 519 us: 1.01x faster                                         |
| regex_compile            | 158 ms                                                       | 157 ms: 1.01x faster                                         |
| deltablue                | 4.00 ms                                                      | 3.97 ms: 1.01x faster                                        |
| json_dumps               | 13.4 ms                                                      | 13.3 ms: 1.01x faster                                        |
| chameleon                | 7.67 ms                                                      | 7.64 ms: 1.00x faster                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 3.09 sec: 1.00x slower                                       |
| scimark_fft              | 285 ms                                                       | 286 ms: 1.00x slower                                         |
| python_startup           | 10.8 ms                                                      | 10.8 ms: 1.01x slower                                        |
| sympy_integrate          | 25.8 ms                                                      | 25.9 ms: 1.01x slower                                        |
| python_startup_no_site   | 7.76 ms                                                      | 7.81 ms: 1.01x slower                                        |
| pathlib                  | 19.1 ms                                                      | 19.2 ms: 1.01x slower                                        |
| tomli_loads              | 2.26 sec                                                     | 2.28 sec: 1.01x slower                                       |
| xml_etree_iterparse      | 104 ms                                                       | 105 ms: 1.01x slower                                         |
| comprehensions           | 24.6 us                                                      | 24.8 us: 1.01x slower                                        |
| scimark_sor              | 111 ms                                                       | 112 ms: 1.01x slower                                         |
| tornado_http             | 122 ms                                                       | 123 ms: 1.01x slower                                         |
| coroutines               | 27.6 ms                                                      | 27.9 ms: 1.01x slower                                        |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.11 ms: 1.01x slower                                        |
| fannkuch                 | 429 ms                                                       | 437 ms: 1.02x slower                                         |
| richards                 | 48.3 ms                                                      | 49.6 ms: 1.03x slower                                        |
| float                    | 74.2 ms                                                      | 76.4 ms: 1.03x slower                                        |
| gc_traversal             | 3.85 ms                                                      | 3.97 ms: 1.03x slower                                        |
| unpickle_list            | 4.53 us                                                      | 4.69 us: 1.03x slower                                        |
| thrift                   | 925 us                                                       | 958 us: 1.04x slower                                         |
| pickle                   | 9.64 us                                                      | 9.99 us: 1.04x slower                                        |
| pickle_dict              | 30.8 us                                                      | 32.1 us: 1.04x slower                                        |
| spectral_norm            | 93.3 ms                                                      | 97.3 ms: 1.04x slower                                        |
| mdp                      | 2.75 sec                                                     | 2.86 sec: 1.04x slower                                       |
| bench_mp_pool            | 4.62 ms                                                      | 4.82 ms: 1.04x slower                                        |
| richards_super           | 61.0 ms                                                      | 63.6 ms: 1.04x slower                                        |
| pidigits                 | 251 ms                                                       | 268 ms: 1.07x slower                                         |
| nbody                    | 90.7 ms                                                      | 96.9 ms: 1.07x slower                                        |
| mypy2                    | 451 ms                                                       | 534 ms: 1.18x slower                                         |
| Geometric mean           | (ref)                                                        | 1.00x faster                                                 |

Benchmark hidden because not significant (21): bench_thread_pool, dask, sqlglot_transpile, async_tree_io, pylint, async_tree_none, sympy_sum, unpack_sequence, aiohttp, sqlite_synth, async_generators, sqlglot_parse, scimark_monte_carlo, flaskblogging, create_gc_cycles, async_tree_cpu_io_mixed, logging_silent, gunicorn, sqlalchemy_declarative, django_template, xml_etree_parse
Ignored benchmarks (1) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: coverage


# HPT report

- Reliability score: 97.75% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
