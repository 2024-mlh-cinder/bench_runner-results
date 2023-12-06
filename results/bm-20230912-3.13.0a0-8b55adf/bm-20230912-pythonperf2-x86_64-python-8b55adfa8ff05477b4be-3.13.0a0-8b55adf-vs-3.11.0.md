
# Results vs. 3.11.0

- fork: python
- ref: 8b55adfa8ff05477b4be
- machine: linux-x86_64
- commit hash: 8b55adf
- commit date: 2023-09-12
- overall geometric mean: 1.05x faster
- HPT reliability: 98.36%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 85.9 ms: 1.06x faster                                                       |
| pidigits       | 251 ms                                                       | 263 ms: 1.05x slower                                                        |
| float          | 74.2 ms                                                      | 80.9 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| regex_v8       | 23.9 ms                                                      | 24.6 ms: 1.03x slower                                                       |
| regex_effbot   | 3.50 ms                                                      | 3.66 ms: 1.05x slower                                                       |
| regex_dna      | 227 ms                                                       | 240 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                                       |
| json_loads           | 28.7 us                                                      | 25.2 us: 1.14x faster                                                       |
| xml_etree_parse      | 158 ms                                                       | 148 ms: 1.06x faster                                                        |
| unpickle_pure_python | 241 us                                                       | 228 us: 1.06x faster                                                        |
| tomli_loads          | 2.26 sec                                                     | 2.19 sec: 1.03x faster                                                      |
| pickle_pure_python   | 319 us                                                       | 314 us: 1.01x faster                                                        |
| xml_etree_iterparse  | 104 ms                                                       | 106 ms: 1.02x slower                                                        |
| xml_etree_process    | 56.5 ms                                                      | 58.3 ms: 1.03x slower                                                       |
| pickle               | 9.64 us                                                      | 10.1 us: 1.05x slower                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                                       |
| pickle_dict          | 30.8 us                                                      | 32.9 us: 1.07x slower                                                       |
| unpickle             | 13.4 us                                                      | 14.5 us: 1.08x slower                                                       |
| pickle_list          | 3.83 us                                                      | 4.37 us: 1.14x slower                                                       |
| Geometric mean       | (ref)                                                        | 1.01x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                                       |
| python_startup         | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.4 ms: 1.05x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230912-pythonperf2-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 153 us: 3.41x faster                                                        |
| asyncio_tcp              | 753 ms                                                       | 372 ms: 2.02x faster                                                        |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.58 sec: 1.95x faster                                                      |
| generators               | 56.0 ms                                                      | 34.5 ms: 1.62x faster                                                       |
| json_dumps               | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                                       |
| chaos                    | 80.9 ms                                                      | 63.6 ms: 1.27x faster                                                       |
| mypy2                    | 451 ms                                                       | 372 ms: 1.21x faster                                                        |
| async_tree_none          | 519 ms                                                       | 433 ms: 1.20x faster                                                        |
| coroutines               | 27.6 ms                                                      | 23.0 ms: 1.20x faster                                                       |
| nqueens                  | 103 ms                                                       | 88.4 ms: 1.16x faster                                                       |
| async_tree_memoization   | 630 ms                                                       | 546 ms: 1.15x faster                                                        |
| crypto_pyaes             | 83.4 ms                                                      | 72.4 ms: 1.15x faster                                                       |
| json_loads               | 28.7 us                                                      | 25.2 us: 1.14x faster                                                       |
| raytrace                 | 317 ms                                                       | 279 ms: 1.13x faster                                                        |
| comprehensions           | 24.6 us                                                      | 21.7 us: 1.13x faster                                                       |
| logging_format           | 8.11 us                                                      | 7.30 us: 1.11x faster                                                       |
| scimark_lu               | 115 ms                                                       | 103 ms: 1.11x faster                                                        |
| hexiom                   | 7.13 ms                                                      | 6.48 ms: 1.10x faster                                                       |
| fannkuch                 | 429 ms                                                       | 390 ms: 1.10x faster                                                        |
| json                     | 5.65 ms                                                      | 5.15 ms: 1.10x faster                                                       |
| mdp                      | 2.75 sec                                                     | 2.51 sec: 1.09x faster                                                      |
| sqlglot_parse            | 1.53 ms                                                      | 1.40 ms: 1.09x faster                                                       |
| deltablue                | 4.00 ms                                                      | 3.67 ms: 1.09x faster                                                       |
| async_tree_io            | 1.17 sec                                                     | 1.08 sec: 1.09x faster                                                      |
| logging_simple           | 7.19 us                                                      | 6.62 us: 1.09x faster                                                       |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 696 ms: 1.08x faster                                                        |
| sqlglot_normalize        | 126 ms                                                       | 118 ms: 1.07x faster                                                        |
| gc_traversal             | 3.85 ms                                                      | 3.60 ms: 1.07x faster                                                       |
| bench_thread_pool        | 1.01 ms                                                      | 949 us: 1.07x faster                                                        |
| xml_etree_parse          | 158 ms                                                       | 148 ms: 1.06x faster                                                        |
| sqlglot_transpile        | 1.92 ms                                                      | 1.81 ms: 1.06x faster                                                       |
| nbody                    | 90.7 ms                                                      | 85.9 ms: 1.06x faster                                                       |
| unpickle_pure_python     | 241 us                                                       | 228 us: 1.06x faster                                                        |
| regex_compile            | 158 ms                                                       | 149 ms: 1.06x faster                                                        |
| mako                     | 11.0 ms                                                      | 10.4 ms: 1.05x faster                                                       |
| deepcopy                 | 399 us                                                       | 382 us: 1.04x faster                                                        |
| scimark_monte_carlo      | 68.2 ms                                                      | 65.4 ms: 1.04x faster                                                       |
| deepcopy_memo            | 38.8 us                                                      | 37.3 us: 1.04x faster                                                       |
| richards_super           | 61.0 ms                                                      | 59.0 ms: 1.04x faster                                                       |
| spectral_norm            | 93.3 ms                                                      | 90.4 ms: 1.03x faster                                                       |
| logging_silent           | 101 ns                                                       | 97.7 ns: 1.03x faster                                                       |
| tomli_loads              | 2.26 sec                                                     | 2.19 sec: 1.03x faster                                                      |
| pycparser                | 1.32 sec                                                     | 1.29 sec: 1.02x faster                                                      |
| deepcopy_reduce          | 3.51 us                                                      | 3.43 us: 1.02x faster                                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 58.9 ms: 1.02x faster                                                       |
| pickle_pure_python       | 319 us                                                       | 314 us: 1.01x faster                                                        |
| coverage                 | 84.8 ms                                                      | 84.0 ms: 1.01x faster                                                       |
| meteor_contest           | 131 ms                                                       | 130 ms: 1.01x faster                                                        |
| docutils                 | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                                      |
| dulwich_log              | 68.4 ms                                                      | 69.3 ms: 1.01x slower                                                       |
| xml_etree_iterparse      | 104 ms                                                       | 106 ms: 1.02x slower                                                        |
| create_gc_cycles         | 1.61 ms                                                      | 1.64 ms: 1.02x slower                                                       |
| pprint_pformat           | 1.63 sec                                                     | 1.66 sec: 1.02x slower                                                      |
| regex_v8                 | 23.9 ms                                                      | 24.6 ms: 1.03x slower                                                       |
| xml_etree_process        | 56.5 ms                                                      | 58.3 ms: 1.03x slower                                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.19 ms: 1.03x slower                                                       |
| pathlib                  | 19.1 ms                                                      | 19.8 ms: 1.04x slower                                                       |
| pprint_safe_repr         | 784 ms                                                       | 816 ms: 1.04x slower                                                        |
| go                       | 164 ms                                                       | 171 ms: 1.04x slower                                                        |
| scimark_fft              | 285 ms                                                       | 298 ms: 1.04x slower                                                        |
| pickle                   | 9.64 us                                                      | 10.1 us: 1.05x slower                                                       |
| regex_effbot             | 3.50 ms                                                      | 3.66 ms: 1.05x slower                                                       |
| pidigits                 | 251 ms                                                       | 263 ms: 1.05x slower                                                        |
| unpack_sequence          | 45.6 ns                                                      | 47.9 ns: 1.05x slower                                                       |
| regex_dna                | 227 ms                                                       | 240 ms: 1.06x slower                                                        |
| xml_etree_generate       | 80.5 ms                                                      | 85.9 ms: 1.07x slower                                                       |
| pickle_dict              | 30.8 us                                                      | 32.9 us: 1.07x slower                                                       |
| sqlite_synth             | 2.50 us                                                      | 2.69 us: 1.07x slower                                                       |
| richards                 | 48.3 ms                                                      | 52.2 ms: 1.08x slower                                                       |
| unpickle                 | 13.4 us                                                      | 14.5 us: 1.08x slower                                                       |
| float                    | 74.2 ms                                                      | 80.9 ms: 1.09x slower                                                       |
| python_startup_no_site   | 7.76 ms                                                      | 8.67 ms: 1.12x slower                                                       |
| pyflate                  | 449 ms                                                       | 509 ms: 1.13x slower                                                        |
| pickle_list              | 3.83 us                                                      | 4.37 us: 1.14x slower                                                       |
| telco                    | 6.86 ms                                                      | 7.97 ms: 1.16x slower                                                       |
| python_startup           | 10.8 ms                                                      | 12.6 ms: 1.17x slower                                                       |
| async_generators         | 316 ms                                                       | 386 ms: 1.22x slower                                                        |
| scimark_sor              | 111 ms                                                       | 148 ms: 1.33x slower                                                        |
| dask                     | 410 ms                                                       | 589 ms: 1.44x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.05x faster                                                                |

Benchmark hidden because not significant (3): tornado_http, bench_mp_pool, unpickle_list
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 98.36% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
