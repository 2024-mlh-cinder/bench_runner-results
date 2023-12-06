
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: ef4bd1b
- commit date: 2023-10-08
- overall geometric mean: 1.07x faster
- HPT reliability: 99.98%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                     |
| Geometric mean | (ref)                                                        | 1.00x slower                                               |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 85.4 ms: 1.06x faster                                      |
| float          | 74.2 ms                                                      | 78.1 ms: 1.05x slower                                      |
| pidigits       | 251 ms                                                       | 265 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 144 ms: 1.10x faster                                       |
| regex_v8       | 23.9 ms                                                      | 23.2 ms: 1.03x faster                                      |
| regex_effbot   | 3.50 ms                                                      | 3.53 ms: 1.01x slower                                      |
| regex_dna      | 227 ms                                                       | 240 ms: 1.06x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                      |
| json_loads           | 28.7 us                                                      | 24.4 us: 1.17x faster                                      |
| unpickle_pure_python | 241 us                                                       | 205 us: 1.17x faster                                       |
| xml_etree_parse      | 158 ms                                                       | 150 ms: 1.06x faster                                       |
| pickle_dict          | 30.8 us                                                      | 31.5 us: 1.02x slower                                      |
| xml_etree_process    | 56.5 ms                                                      | 58.3 ms: 1.03x slower                                      |
| pickle               | 9.64 us                                                      | 10.0 us: 1.04x slower                                      |
| xml_etree_generate   | 80.5 ms                                                      | 86.6 ms: 1.08x slower                                      |
| unpickle             | 13.4 us                                                      | 14.8 us: 1.10x slower                                      |
| unpickle_list        | 4.53 us                                                      | 5.03 us: 1.11x slower                                      |
| pickle_list          | 3.83 us                                                      | 4.32 us: 1.13x slower                                      |
| Geometric mean       | (ref)                                                        | 1.01x faster                                               |

Benchmark hidden because not significant (3): tomli_loads, pickle_pure_python, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                      |
| python_startup_no_site | 7.76 ms                                                      | 8.65 ms: 1.12x slower                                      |
| Geometric mean         | (ref)                                                        | 1.10x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 152 us: 3.45x faster                                       |
| asyncio_tcp              | 753 ms                                                       | 379 ms: 1.99x faster                                       |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.57 sec: 1.97x faster                                     |
| generators               | 56.0 ms                                                      | 37.2 ms: 1.51x faster                                      |
| json_dumps               | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                      |
| chaos                    | 80.9 ms                                                      | 63.9 ms: 1.27x faster                                      |
| deltablue                | 4.00 ms                                                      | 3.23 ms: 1.24x faster                                      |
| fannkuch                 | 429 ms                                                       | 354 ms: 1.21x faster                                       |
| hexiom                   | 7.13 ms                                                      | 5.95 ms: 1.20x faster                                      |
| coroutines               | 27.6 ms                                                      | 23.1 ms: 1.19x faster                                      |
| richards_super           | 61.0 ms                                                      | 51.6 ms: 1.18x faster                                      |
| json_loads               | 28.7 us                                                      | 24.4 us: 1.17x faster                                      |
| unpickle_pure_python     | 241 us                                                       | 205 us: 1.17x faster                                       |
| scimark_lu               | 115 ms                                                       | 99.8 ms: 1.15x faster                                      |
| async_tree_memoization   | 630 ms                                                       | 551 ms: 1.14x faster                                       |
| async_tree_none          | 519 ms                                                       | 459 ms: 1.13x faster                                       |
| nqueens                  | 103 ms                                                       | 91.1 ms: 1.13x faster                                      |
| comprehensions           | 24.6 us                                                      | 21.9 us: 1.12x faster                                      |
| logging_format           | 8.11 us                                                      | 7.25 us: 1.12x faster                                      |
| async_tree_io            | 1.17 sec                                                     | 1.06 sec: 1.11x faster                                     |
| go                       | 164 ms                                                       | 148 ms: 1.11x faster                                       |
| sqlglot_parse            | 1.53 ms                                                      | 1.38 ms: 1.11x faster                                      |
| logging_simple           | 7.19 us                                                      | 6.50 us: 1.11x faster                                      |
| gc_traversal             | 3.85 ms                                                      | 3.50 ms: 1.10x faster                                      |
| regex_compile            | 158 ms                                                       | 144 ms: 1.10x faster                                       |
| json                     | 5.65 ms                                                      | 5.17 ms: 1.09x faster                                      |
| mako                     | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                      |
| mdp                      | 2.75 sec                                                     | 2.54 sec: 1.08x faster                                     |
| sqlglot_transpile        | 1.92 ms                                                      | 1.78 ms: 1.08x faster                                      |
| logging_silent           | 101 ns                                                       | 93.8 ns: 1.07x faster                                      |
| richards                 | 48.3 ms                                                      | 45.0 ms: 1.07x faster                                      |
| sqlglot_normalize        | 126 ms                                                       | 118 ms: 1.07x faster                                       |
| deepcopy                 | 399 us                                                       | 373 us: 1.07x faster                                       |
| pycparser                | 1.32 sec                                                     | 1.24 sec: 1.07x faster                                     |
| nbody                    | 90.7 ms                                                      | 85.4 ms: 1.06x faster                                      |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 707 ms: 1.06x faster                                       |
| bench_thread_pool        | 1.01 ms                                                      | 956 us: 1.06x faster                                       |
| dulwich_log              | 68.4 ms                                                      | 64.8 ms: 1.06x faster                                      |
| xml_etree_parse          | 158 ms                                                       | 150 ms: 1.06x faster                                       |
| deepcopy_memo            | 38.8 us                                                      | 36.9 us: 1.05x faster                                      |
| crypto_pyaes             | 83.4 ms                                                      | 79.9 ms: 1.04x faster                                      |
| raytrace                 | 317 ms                                                       | 303 ms: 1.04x faster                                       |
| dask                     | 410 ms                                                       | 395 ms: 1.04x faster                                       |
| meteor_contest           | 131 ms                                                       | 126 ms: 1.04x faster                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 57.7 ms: 1.04x faster                                      |
| regex_v8                 | 23.9 ms                                                      | 23.2 ms: 1.03x faster                                      |
| deepcopy_reduce          | 3.51 us                                                      | 3.43 us: 1.02x faster                                      |
| spectral_norm            | 93.3 ms                                                      | 91.3 ms: 1.02x faster                                      |
| pprint_pformat           | 1.63 sec                                                     | 1.61 sec: 1.01x faster                                     |
| scimark_sor              | 111 ms                                                       | 110 ms: 1.01x faster                                       |
| pprint_safe_repr         | 784 ms                                                       | 791 ms: 1.01x slower                                       |
| docutils                 | 2.86 sec                                                     | 2.88 sec: 1.01x slower                                     |
| regex_effbot             | 3.50 ms                                                      | 3.53 ms: 1.01x slower                                      |
| pathlib                  | 19.1 ms                                                      | 19.3 ms: 1.01x slower                                      |
| coverage                 | 84.8 ms                                                      | 86.6 ms: 1.02x slower                                      |
| pickle_dict              | 30.8 us                                                      | 31.5 us: 1.02x slower                                      |
| xml_etree_process        | 56.5 ms                                                      | 58.3 ms: 1.03x slower                                      |
| unpack_sequence          | 45.6 ns                                                      | 47.4 ns: 1.04x slower                                      |
| pickle                   | 9.64 us                                                      | 10.0 us: 1.04x slower                                      |
| telco                    | 6.86 ms                                                      | 7.14 ms: 1.04x slower                                      |
| scimark_fft              | 285 ms                                                       | 299 ms: 1.05x slower                                       |
| float                    | 74.2 ms                                                      | 78.1 ms: 1.05x slower                                      |
| pidigits                 | 251 ms                                                       | 265 ms: 1.05x slower                                       |
| regex_dna                | 227 ms                                                       | 240 ms: 1.06x slower                                       |
| scimark_monte_carlo      | 68.2 ms                                                      | 72.5 ms: 1.06x slower                                      |
| xml_etree_generate       | 80.5 ms                                                      | 86.6 ms: 1.08x slower                                      |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.38 ms: 1.08x slower                                      |
| python_startup           | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                      |
| sqlite_synth             | 2.50 us                                                      | 2.72 us: 1.09x slower                                      |
| unpickle                 | 13.4 us                                                      | 14.8 us: 1.10x slower                                      |
| unpickle_list            | 4.53 us                                                      | 5.03 us: 1.11x slower                                      |
| python_startup_no_site   | 7.76 ms                                                      | 8.65 ms: 1.12x slower                                      |
| pickle_list              | 3.83 us                                                      | 4.32 us: 1.13x slower                                      |
| async_generators         | 316 ms                                                       | 386 ms: 1.22x slower                                       |
| bench_mp_pool            | 4.62 ms                                                      | 6.96 ms: 1.51x slower                                      |
| Geometric mean           | (ref)                                                        | 1.07x faster                                               |

Benchmark hidden because not significant (8): tornado_http, tomli_loads, pyflate, 2to3, pickle_pure_python, create_gc_cycles, xml_etree_iterparse, mypy2
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
