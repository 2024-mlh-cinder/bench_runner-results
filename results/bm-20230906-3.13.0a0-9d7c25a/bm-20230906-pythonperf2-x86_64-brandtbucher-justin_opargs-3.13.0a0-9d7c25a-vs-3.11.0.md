
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_opargs
- machine: linux-x86_64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.02x faster
- HPT reliability: 78.06%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.95 sec: 1.03x slower                                                     |
| Geometric mean | (ref)                                                        | 1.02x slower                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 93.4 ms: 1.03x slower                                                      |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                       |
| float          | 74.2 ms                                                      | 82.9 ms: 1.12x slower                                                      |
| Geometric mean | (ref)                                                        | 1.07x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 156 ms: 1.01x faster                                                       |
| regex_effbot   | 3.50 ms                                                      | 3.56 ms: 1.02x slower                                                      |
| regex_v8       | 23.9 ms                                                      | 25.8 ms: 1.08x slower                                                      |
| regex_dna      | 227 ms                                                       | 248 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                                      |
| json_loads           | 28.7 us                                                      | 25.1 us: 1.14x faster                                                      |
| xml_etree_parse      | 158 ms                                                       | 148 ms: 1.07x faster                                                       |
| pickle_pure_python   | 319 us                                                       | 317 us: 1.01x faster                                                       |
| unpickle_pure_python | 241 us                                                       | 242 us: 1.01x slower                                                       |
| unpickle_list        | 4.53 us                                                      | 4.68 us: 1.03x slower                                                      |
| xml_etree_iterparse  | 104 ms                                                       | 108 ms: 1.03x slower                                                       |
| pickle_dict          | 30.8 us                                                      | 31.9 us: 1.04x slower                                                      |
| pickle               | 9.64 us                                                      | 10.1 us: 1.04x slower                                                      |
| tomli_loads          | 2.26 sec                                                     | 2.38 sec: 1.05x slower                                                     |
| xml_etree_process    | 56.5 ms                                                      | 60.2 ms: 1.07x slower                                                      |
| unpickle             | 13.4 us                                                      | 14.4 us: 1.07x slower                                                      |
| xml_etree_generate   | 80.5 ms                                                      | 86.3 ms: 1.07x slower                                                      |
| pickle_list          | 3.83 us                                                      | 4.51 us: 1.18x slower                                                      |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 12.3 ms: 1.14x slower                                                      |
| python_startup_no_site | 7.76 ms                                                      | 9.26 ms: 1.19x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.17x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.6 ms: 1.04x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 156 us: 3.35x faster                                                       |
| asyncio_tcp              | 753 ms                                                       | 372 ms: 2.02x faster                                                       |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                                     |
| generators               | 56.0 ms                                                      | 36.9 ms: 1.52x faster                                                      |
| json_dumps               | 13.4 ms                                                      | 10.6 ms: 1.26x faster                                                      |
| chaos                    | 80.9 ms                                                      | 66.9 ms: 1.21x faster                                                      |
| coroutines               | 27.6 ms                                                      | 23.1 ms: 1.19x faster                                                      |
| async_tree_none          | 519 ms                                                       | 441 ms: 1.18x faster                                                       |
| mypy2                    | 451 ms                                                       | 386 ms: 1.17x faster                                                       |
| json_loads               | 28.7 us                                                      | 25.1 us: 1.14x faster                                                      |
| raytrace                 | 317 ms                                                       | 279 ms: 1.14x faster                                                       |
| async_tree_memoization   | 630 ms                                                       | 555 ms: 1.14x faster                                                       |
| crypto_pyaes             | 83.4 ms                                                      | 74.2 ms: 1.12x faster                                                      |
| gc_traversal             | 3.85 ms                                                      | 3.48 ms: 1.11x faster                                                      |
| json                     | 5.65 ms                                                      | 5.13 ms: 1.10x faster                                                      |
| scimark_lu               | 115 ms                                                       | 106 ms: 1.08x faster                                                       |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.07x faster                                                     |
| xml_etree_parse          | 158 ms                                                       | 148 ms: 1.07x faster                                                       |
| logging_format           | 8.11 us                                                      | 7.61 us: 1.07x faster                                                      |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 707 ms: 1.06x faster                                                       |
| deltablue                | 4.00 ms                                                      | 3.78 ms: 1.06x faster                                                      |
| sqlglot_parse            | 1.53 ms                                                      | 1.46 ms: 1.05x faster                                                      |
| logging_simple           | 7.19 us                                                      | 6.88 us: 1.05x faster                                                      |
| mdp                      | 2.75 sec                                                     | 2.64 sec: 1.04x faster                                                     |
| mako                     | 11.0 ms                                                      | 10.6 ms: 1.04x faster                                                      |
| sqlglot_normalize        | 126 ms                                                       | 122 ms: 1.04x faster                                                       |
| create_gc_cycles         | 1.61 ms                                                      | 1.56 ms: 1.03x faster                                                      |
| coverage                 | 84.8 ms                                                      | 82.5 ms: 1.03x faster                                                      |
| sqlglot_transpile        | 1.92 ms                                                      | 1.88 ms: 1.02x faster                                                      |
| fannkuch                 | 429 ms                                                       | 421 ms: 1.02x faster                                                       |
| deepcopy_reduce          | 3.51 us                                                      | 3.46 us: 1.02x faster                                                      |
| deepcopy                 | 399 us                                                       | 396 us: 1.01x faster                                                       |
| logging_silent           | 101 ns                                                       | 100.0 ns: 1.01x faster                                                     |
| regex_compile            | 158 ms                                                       | 156 ms: 1.01x faster                                                       |
| richards_super           | 61.0 ms                                                      | 60.6 ms: 1.01x faster                                                      |
| pickle_pure_python       | 319 us                                                       | 317 us: 1.01x faster                                                       |
| unpickle_pure_python     | 241 us                                                       | 242 us: 1.01x slower                                                       |
| pycparser                | 1.32 sec                                                     | 1.33 sec: 1.01x slower                                                     |
| nqueens                  | 103 ms                                                       | 104 ms: 1.01x slower                                                       |
| deepcopy_memo            | 38.8 us                                                      | 39.4 us: 1.02x slower                                                      |
| dulwich_log              | 68.4 ms                                                      | 69.5 ms: 1.02x slower                                                      |
| regex_effbot             | 3.50 ms                                                      | 3.56 ms: 1.02x slower                                                      |
| spectral_norm            | 93.3 ms                                                      | 95.2 ms: 1.02x slower                                                      |
| pprint_pformat           | 1.63 sec                                                     | 1.66 sec: 1.02x slower                                                     |
| comprehensions           | 24.6 us                                                      | 25.2 us: 1.03x slower                                                      |
| sqlglot_optimize         | 59.8 ms                                                      | 61.4 ms: 1.03x slower                                                      |
| nbody                    | 90.7 ms                                                      | 93.4 ms: 1.03x slower                                                      |
| unpickle_list            | 4.53 us                                                      | 4.68 us: 1.03x slower                                                      |
| docutils                 | 2.86 sec                                                     | 2.95 sec: 1.03x slower                                                     |
| pathlib                  | 19.1 ms                                                      | 19.7 ms: 1.03x slower                                                      |
| xml_etree_iterparse      | 104 ms                                                       | 108 ms: 1.03x slower                                                       |
| pickle_dict              | 30.8 us                                                      | 31.9 us: 1.04x slower                                                      |
| hexiom                   | 7.13 ms                                                      | 7.40 ms: 1.04x slower                                                      |
| pprint_safe_repr         | 784 ms                                                       | 815 ms: 1.04x slower                                                       |
| scimark_monte_carlo      | 68.2 ms                                                      | 71.1 ms: 1.04x slower                                                      |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.04x slower                                                      |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                                       |
| tomli_loads              | 2.26 sec                                                     | 2.38 sec: 1.05x slower                                                     |
| bench_mp_pool            | 4.62 ms                                                      | 4.90 ms: 1.06x slower                                                      |
| meteor_contest           | 131 ms                                                       | 139 ms: 1.06x slower                                                       |
| xml_etree_process        | 56.5 ms                                                      | 60.2 ms: 1.07x slower                                                      |
| unpickle                 | 13.4 us                                                      | 14.4 us: 1.07x slower                                                      |
| xml_etree_generate       | 80.5 ms                                                      | 86.3 ms: 1.07x slower                                                      |
| regex_v8                 | 23.9 ms                                                      | 25.8 ms: 1.08x slower                                                      |
| sqlite_synth             | 2.50 us                                                      | 2.73 us: 1.09x slower                                                      |
| go                       | 164 ms                                                       | 179 ms: 1.09x slower                                                       |
| regex_dna                | 227 ms                                                       | 248 ms: 1.09x slower                                                       |
| richards                 | 48.3 ms                                                      | 53.8 ms: 1.11x slower                                                      |
| float                    | 74.2 ms                                                      | 82.9 ms: 1.12x slower                                                      |
| pyflate                  | 449 ms                                                       | 503 ms: 1.12x slower                                                       |
| python_startup           | 10.8 ms                                                      | 12.3 ms: 1.14x slower                                                      |
| scimark_fft              | 285 ms                                                       | 334 ms: 1.17x slower                                                       |
| telco                    | 6.86 ms                                                      | 8.07 ms: 1.18x slower                                                      |
| pickle_list              | 3.83 us                                                      | 4.51 us: 1.18x slower                                                      |
| python_startup_no_site   | 7.76 ms                                                      | 9.26 ms: 1.19x slower                                                      |
| unpack_sequence          | 45.6 ns                                                      | 56.2 ns: 1.23x slower                                                      |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 5.12 ms: 1.26x slower                                                      |
| async_generators         | 316 ms                                                       | 409 ms: 1.30x slower                                                       |
| scimark_sor              | 111 ms                                                       | 150 ms: 1.35x slower                                                       |
| dask                     | 410 ms                                                       | 596 ms: 1.45x slower                                                       |
| Geometric mean           | (ref)                                                        | 1.02x faster                                                               |

Benchmark hidden because not significant (2): bench_thread_pool, tornado_http
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 78.06% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
