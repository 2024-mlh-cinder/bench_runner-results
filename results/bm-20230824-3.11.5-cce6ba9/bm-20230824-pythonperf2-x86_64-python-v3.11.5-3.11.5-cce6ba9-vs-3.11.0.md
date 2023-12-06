
# Results vs. 3.11.0

- fork: python
- ref: v3.11.5
- machine: linux-x86_64
- commit hash: cce6ba9
- commit date: 2023-08-24
- overall geometric mean: 1.00x slower
- HPT reliability: 98.83%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 285 ms: 1.01x faster                                         |
| chameleon      | 7.67 ms                                                      | 7.28 ms: 1.05x faster                                        |
| docutils       | 2.86 sec                                                     | 2.84 sec: 1.01x faster                                       |
| html5lib       | 72.9 ms                                                      | 71.4 ms: 1.02x faster                                        |
| tornado_http   | 122 ms                                                       | 124 ms: 1.02x slower                                         |
| Geometric mean | (ref)                                                        | 1.01x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 251 ms: 1.00x faster                                         |
| Geometric mean | (ref)                                                        | 1.00x faster                                                 |

Benchmark hidden because not significant (2): nbody, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot   | 3.50 ms                                                      | 3.31 ms: 1.06x faster                                        |
| regex_compile  | 158 ms                                                       | 155 ms: 1.02x faster                                         |
| regex_v8       | 23.9 ms                                                      | 24.2 ms: 1.01x slower                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                 |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|---------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| json_loads          | 28.7 us                                                      | 27.9 us: 1.03x faster                                        |
| xml_etree_iterparse | 104 ms                                                       | 103 ms: 1.01x faster                                         |
| unpickle            | 13.4 us                                                      | 13.3 us: 1.01x faster                                        |
| xml_etree_process   | 56.5 ms                                                      | 56.1 ms: 1.01x faster                                        |
| xml_etree_generate  | 80.5 ms                                                      | 80.8 ms: 1.00x slower                                        |
| json_dumps          | 13.4 ms                                                      | 13.5 ms: 1.01x slower                                        |
| unpickle_list       | 4.53 us                                                      | 4.63 us: 1.02x slower                                        |
| pickle_list         | 3.83 us                                                      | 3.94 us: 1.03x slower                                        |
| pickle              | 9.64 us                                                      | 9.98 us: 1.04x slower                                        |
| pickle_dict         | 30.8 us                                                      | 33.1 us: 1.07x slower                                        |
| Geometric mean      | (ref)                                                        | 1.01x slower                                                 |

Benchmark hidden because not significant (4): xml_etree_parse, unpickle_pure_python, pickle_pure_python, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.8 ms: 1.00x slower                                        |
| python_startup_no_site | 7.76 ms                                                      | 7.79 ms: 1.00x slower                                        |
| Geometric mean         | (ref)                                                        | 1.00x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| genshi_xml     | 58.5 ms                                                      | 55.7 ms: 1.05x faster                                        |
| mako           | 11.0 ms                                                      | 10.6 ms: 1.03x faster                                        |
| genshi_text    | 26.1 ms                                                      | 25.5 ms: 1.03x faster                                        |
| Geometric mean | (ref)                                                        | 1.02x faster                                                 |

Benchmark hidden because not significant (1): django_template

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_effbot             | 3.50 ms                                                      | 3.31 ms: 1.06x faster                                        |
| chameleon                | 7.67 ms                                                      | 7.28 ms: 1.05x faster                                        |
| genshi_xml               | 58.5 ms                                                      | 55.7 ms: 1.05x faster                                        |
| dulwich_log              | 68.4 ms                                                      | 65.3 ms: 1.05x faster                                        |
| deepcopy_memo            | 38.8 us                                                      | 37.4 us: 1.04x faster                                        |
| logging_format           | 8.11 us                                                      | 7.83 us: 1.04x faster                                        |
| mako                     | 11.0 ms                                                      | 10.6 ms: 1.03x faster                                        |
| deepcopy_reduce          | 3.51 us                                                      | 3.40 us: 1.03x faster                                        |
| sqlalchemy_imperative    | 20.1 ms                                                      | 19.5 ms: 1.03x faster                                        |
| json_loads               | 28.7 us                                                      | 27.9 us: 1.03x faster                                        |
| genshi_text              | 26.1 ms                                                      | 25.5 ms: 1.03x faster                                        |
| chaos                    | 80.9 ms                                                      | 79.1 ms: 1.02x faster                                        |
| bench_thread_pool        | 1.01 ms                                                      | 989 us: 1.02x faster                                         |
| crypto_pyaes             | 83.4 ms                                                      | 81.7 ms: 1.02x faster                                        |
| html5lib                 | 72.9 ms                                                      | 71.4 ms: 1.02x faster                                        |
| gc_traversal             | 3.85 ms                                                      | 3.77 ms: 1.02x faster                                        |
| pyflate                  | 449 ms                                                       | 441 ms: 1.02x faster                                         |
| scimark_fft              | 285 ms                                                       | 280 ms: 1.02x faster                                         |
| json                     | 5.65 ms                                                      | 5.55 ms: 1.02x faster                                        |
| telco                    | 6.86 ms                                                      | 6.75 ms: 1.02x faster                                        |
| sqlglot_optimize         | 59.8 ms                                                      | 58.9 ms: 1.02x faster                                        |
| regex_compile            | 158 ms                                                       | 155 ms: 1.02x faster                                         |
| pprint_pformat           | 1.63 sec                                                     | 1.61 sec: 1.01x faster                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.00 ms: 1.01x faster                                        |
| flaskblogging            | 3.88 ms                                                      | 3.83 ms: 1.01x faster                                        |
| xml_etree_iterparse      | 104 ms                                                       | 103 ms: 1.01x faster                                         |
| sqlglot_normalize        | 126 ms                                                       | 124 ms: 1.01x faster                                         |
| unpickle                 | 13.4 us                                                      | 13.3 us: 1.01x faster                                        |
| generators               | 56.0 ms                                                      | 55.4 ms: 1.01x faster                                        |
| pprint_safe_repr         | 784 ms                                                       | 775 ms: 1.01x faster                                         |
| nqueens                  | 103 ms                                                       | 102 ms: 1.01x faster                                         |
| scimark_lu               | 115 ms                                                       | 113 ms: 1.01x faster                                         |
| deepcopy                 | 399 us                                                       | 396 us: 1.01x faster                                         |
| 2to3                     | 288 ms                                                       | 285 ms: 1.01x faster                                         |
| async_tree_memoization   | 630 ms                                                       | 624 ms: 1.01x faster                                         |
| typing_runtime_protocols | 523 us                                                       | 518 us: 1.01x faster                                         |
| logging_silent           | 101 ns                                                       | 100 ns: 1.01x faster                                         |
| docutils                 | 2.86 sec                                                     | 2.84 sec: 1.01x faster                                       |
| sympy_integrate          | 25.8 ms                                                      | 25.6 ms: 1.01x faster                                        |
| xml_etree_process        | 56.5 ms                                                      | 56.1 ms: 1.01x faster                                        |
| sympy_str                | 337 ms                                                       | 336 ms: 1.00x faster                                         |
| pathlib                  | 19.1 ms                                                      | 19.0 ms: 1.00x faster                                        |
| pidigits                 | 251 ms                                                       | 251 ms: 1.00x faster                                         |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 3.08 sec: 1.00x slower                                       |
| meteor_contest           | 131 ms                                                       | 131 ms: 1.00x slower                                         |
| python_startup           | 10.8 ms                                                      | 10.8 ms: 1.00x slower                                        |
| xml_etree_generate       | 80.5 ms                                                      | 80.8 ms: 1.00x slower                                        |
| python_startup_no_site   | 7.76 ms                                                      | 7.79 ms: 1.00x slower                                        |
| coroutines               | 27.6 ms                                                      | 27.7 ms: 1.01x slower                                        |
| aiohttp                  | 985 us                                                       | 991 us: 1.01x slower                                         |
| async_generators         | 316 ms                                                       | 318 ms: 1.01x slower                                         |
| deltablue                | 4.00 ms                                                      | 4.03 ms: 1.01x slower                                        |
| json_dumps               | 13.4 ms                                                      | 13.5 ms: 1.01x slower                                        |
| regex_v8                 | 23.9 ms                                                      | 24.2 ms: 1.01x slower                                        |
| hexiom                   | 7.13 ms                                                      | 7.21 ms: 1.01x slower                                        |
| mdp                      | 2.75 sec                                                     | 2.78 sec: 1.01x slower                                       |
| scimark_monte_carlo      | 68.2 ms                                                      | 69.0 ms: 1.01x slower                                        |
| tornado_http             | 122 ms                                                       | 124 ms: 1.02x slower                                         |
| comprehensions           | 24.6 us                                                      | 25.0 us: 1.02x slower                                        |
| logging_simple           | 7.19 us                                                      | 7.33 us: 1.02x slower                                        |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 765 ms: 1.02x slower                                         |
| unpickle_list            | 4.53 us                                                      | 4.63 us: 1.02x slower                                        |
| sqlite_synth             | 2.50 us                                                      | 2.55 us: 1.02x slower                                        |
| unpack_sequence          | 45.6 ns                                                      | 46.9 ns: 1.03x slower                                        |
| gunicorn                 | 973 us                                                       | 999 us: 1.03x slower                                         |
| pickle_list              | 3.83 us                                                      | 3.94 us: 1.03x slower                                        |
| pickle                   | 9.64 us                                                      | 9.98 us: 1.04x slower                                        |
| richards_super           | 61.0 ms                                                      | 64.3 ms: 1.05x slower                                        |
| thrift                   | 925 us                                                       | 986 us: 1.07x slower                                         |
| richards                 | 48.3 ms                                                      | 51.6 ms: 1.07x slower                                        |
| pickle_dict              | 30.8 us                                                      | 33.1 us: 1.07x slower                                        |
| fannkuch                 | 429 ms                                                       | 470 ms: 1.10x slower                                         |
| mypy2                    | 451 ms                                                       | 537 ms: 1.19x slower                                         |
| Geometric mean           | (ref)                                                        | 1.00x slower                                                 |

Benchmark hidden because not significant (25): go, xml_etree_parse, async_tree_none, sqlglot_transpile, nbody, dask, sympy_sum, pycparser, async_tree_io, spectral_norm, regex_dna, unpickle_pure_python, scimark_sor, asyncio_tcp, sympy_expand, sqlalchemy_declarative, float, pickle_pure_python, pylint, sqlglot_parse, raytrace, create_gc_cycles, django_template, tomli_loads, bench_mp_pool
Ignored benchmarks (1) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: coverage


# HPT report

- Reliability score: 98.83% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
