
# Results vs. 3.11.0

- fork: python
- ref: 19b7ead5eb2fd1a0d194
- machine: linux-x86_64
- commit hash: 19b7ead
- commit date: 2023-10-12
- overall geometric mean: 1.05x faster
- HPT reliability: 94.40%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                                      |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 88.5 ms: 1.02x faster                                                       |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                        |
| float          | 74.2 ms                                                      | 80.3 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| regex_effbot   | 3.50 ms                                                      | 3.46 ms: 1.01x faster                                                       |
| regex_v8       | 23.9 ms                                                      | 24.9 ms: 1.04x slower                                                       |
| regex_dna      | 227 ms                                                       | 238 ms: 1.05x slower                                                        |
| Geometric mean | (ref)                                                        | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.5 ms: 1.28x faster                                                       |
| json_loads           | 28.7 us                                                      | 24.2 us: 1.19x faster                                                       |
| unpickle_pure_python | 241 us                                                       | 227 us: 1.06x faster                                                        |
| xml_etree_parse      | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| pickle_pure_python   | 319 us                                                       | 312 us: 1.02x faster                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 107 ms: 1.03x slower                                                        |
| xml_etree_process    | 56.5 ms                                                      | 58.0 ms: 1.03x slower                                                       |
| tomli_loads          | 2.26 sec                                                     | 2.36 sec: 1.04x slower                                                      |
| unpickle_list        | 4.53 us                                                      | 4.73 us: 1.04x slower                                                       |
| unpickle             | 13.4 us                                                      | 14.1 us: 1.05x slower                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 84.8 ms: 1.05x slower                                                       |
| pickle_dict          | 30.8 us                                                      | 32.5 us: 1.05x slower                                                       |
| pickle               | 9.64 us                                                      | 10.2 us: 1.06x slower                                                       |
| pickle_list          | 3.83 us                                                      | 4.45 us: 1.16x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.00x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                                       |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 150 us: 3.48x faster                                                        |
| asyncio_tcp              | 753 ms                                                       | 366 ms: 2.06x faster                                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                                      |
| generators               | 56.0 ms                                                      | 35.2 ms: 1.59x faster                                                       |
| chaos                    | 80.9 ms                                                      | 61.2 ms: 1.32x faster                                                       |
| json_dumps               | 13.4 ms                                                      | 10.5 ms: 1.28x faster                                                       |
| mypy2                    | 451 ms                                                       | 371 ms: 1.22x faster                                                        |
| async_tree_none          | 519 ms                                                       | 437 ms: 1.19x faster                                                        |
| json_loads               | 28.7 us                                                      | 24.2 us: 1.19x faster                                                       |
| coroutines               | 27.6 ms                                                      | 23.5 ms: 1.17x faster                                                       |
| nqueens                  | 103 ms                                                       | 88.1 ms: 1.17x faster                                                       |
| crypto_pyaes             | 83.4 ms                                                      | 72.1 ms: 1.16x faster                                                       |
| async_tree_memoization   | 630 ms                                                       | 552 ms: 1.14x faster                                                        |
| raytrace                 | 317 ms                                                       | 279 ms: 1.13x faster                                                        |
| scimark_lu               | 115 ms                                                       | 102 ms: 1.12x faster                                                        |
| comprehensions           | 24.6 us                                                      | 22.0 us: 1.12x faster                                                       |
| hexiom                   | 7.13 ms                                                      | 6.39 ms: 1.12x faster                                                       |
| json                     | 5.65 ms                                                      | 5.12 ms: 1.10x faster                                                       |
| fannkuch                 | 429 ms                                                       | 392 ms: 1.09x faster                                                        |
| deltablue                | 4.00 ms                                                      | 3.66 ms: 1.09x faster                                                       |
| mdp                      | 2.75 sec                                                     | 2.52 sec: 1.09x faster                                                      |
| sqlglot_parse            | 1.53 ms                                                      | 1.41 ms: 1.08x faster                                                       |
| sqlglot_normalize        | 126 ms                                                       | 116 ms: 1.08x faster                                                        |
| logging_format           | 8.11 us                                                      | 7.50 us: 1.08x faster                                                       |
| async_tree_io            | 1.17 sec                                                     | 1.09 sec: 1.08x faster                                                      |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 699 ms: 1.07x faster                                                        |
| mako                     | 11.0 ms                                                      | 10.3 ms: 1.07x faster                                                       |
| deepcopy                 | 399 us                                                       | 375 us: 1.07x faster                                                        |
| unpickle_pure_python     | 241 us                                                       | 227 us: 1.06x faster                                                        |
| xml_etree_parse          | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| regex_compile            | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| sqlglot_transpile        | 1.92 ms                                                      | 1.82 ms: 1.05x faster                                                       |
| bench_thread_pool        | 1.01 ms                                                      | 962 us: 1.05x faster                                                        |
| deepcopy_memo            | 38.8 us                                                      | 37.0 us: 1.05x faster                                                       |
| logging_simple           | 7.19 us                                                      | 6.88 us: 1.05x faster                                                       |
| deepcopy_reduce          | 3.51 us                                                      | 3.37 us: 1.04x faster                                                       |
| gc_traversal             | 3.85 ms                                                      | 3.71 ms: 1.04x faster                                                       |
| logging_silent           | 101 ns                                                       | 97.3 ns: 1.04x faster                                                       |
| coverage                 | 84.8 ms                                                      | 82.5 ms: 1.03x faster                                                       |
| nbody                    | 90.7 ms                                                      | 88.5 ms: 1.02x faster                                                       |
| pycparser                | 1.32 sec                                                     | 1.29 sec: 1.02x faster                                                      |
| pickle_pure_python       | 319 us                                                       | 312 us: 1.02x faster                                                        |
| sqlglot_optimize         | 59.8 ms                                                      | 58.4 ms: 1.02x faster                                                       |
| spectral_norm            | 93.3 ms                                                      | 91.7 ms: 1.02x faster                                                       |
| tornado_http             | 122 ms                                                       | 120 ms: 1.02x faster                                                        |
| richards_super           | 61.0 ms                                                      | 60.2 ms: 1.01x faster                                                       |
| regex_effbot             | 3.50 ms                                                      | 3.46 ms: 1.01x faster                                                       |
| docutils                 | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                                      |
| pprint_pformat           | 1.63 sec                                                     | 1.65 sec: 1.01x slower                                                      |
| meteor_contest           | 131 ms                                                       | 133 ms: 1.02x slower                                                        |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.12 ms: 1.02x slower                                                       |
| create_gc_cycles         | 1.61 ms                                                      | 1.64 ms: 1.02x slower                                                       |
| dulwich_log              | 68.4 ms                                                      | 70.0 ms: 1.02x slower                                                       |
| pathlib                  | 19.1 ms                                                      | 19.5 ms: 1.02x slower                                                       |
| scimark_monte_carlo      | 68.2 ms                                                      | 69.8 ms: 1.02x slower                                                       |
| xml_etree_iterparse      | 104 ms                                                       | 107 ms: 1.03x slower                                                        |
| xml_etree_process        | 56.5 ms                                                      | 58.0 ms: 1.03x slower                                                       |
| pprint_safe_repr         | 784 ms                                                       | 809 ms: 1.03x slower                                                        |
| go                       | 164 ms                                                       | 170 ms: 1.03x slower                                                        |
| regex_v8                 | 23.9 ms                                                      | 24.9 ms: 1.04x slower                                                       |
| tomli_loads              | 2.26 sec                                                     | 2.36 sec: 1.04x slower                                                      |
| unpickle_list            | 4.53 us                                                      | 4.73 us: 1.04x slower                                                       |
| scimark_fft              | 285 ms                                                       | 298 ms: 1.04x slower                                                        |
| unpickle                 | 13.4 us                                                      | 14.1 us: 1.05x slower                                                       |
| regex_dna                | 227 ms                                                       | 238 ms: 1.05x slower                                                        |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                                        |
| xml_etree_generate       | 80.5 ms                                                      | 84.8 ms: 1.05x slower                                                       |
| pickle_dict              | 30.8 us                                                      | 32.5 us: 1.05x slower                                                       |
| pickle                   | 9.64 us                                                      | 10.2 us: 1.06x slower                                                       |
| float                    | 74.2 ms                                                      | 80.3 ms: 1.08x slower                                                       |
| sqlite_synth             | 2.50 us                                                      | 2.71 us: 1.08x slower                                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.69 ms: 1.12x slower                                                       |
| richards                 | 48.3 ms                                                      | 54.9 ms: 1.14x slower                                                       |
| pyflate                  | 449 ms                                                       | 514 ms: 1.15x slower                                                        |
| pickle_list              | 3.83 us                                                      | 4.45 us: 1.16x slower                                                       |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                                       |
| unpack_sequence          | 45.6 ns                                                      | 54.1 ns: 1.19x slower                                                       |
| telco                    | 6.86 ms                                                      | 8.20 ms: 1.20x slower                                                       |
| async_generators         | 316 ms                                                       | 386 ms: 1.22x slower                                                        |
| scimark_sor              | 111 ms                                                       | 149 ms: 1.34x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                                |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 94.40% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
