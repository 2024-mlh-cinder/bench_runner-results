
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.06x faster
- HPT reliability: 99.94%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 288 ms                                                       | 287 ms: 1.00x faster                                       |
| docutils       | 2.86 sec                                                     | 2.87 sec: 1.01x slower                                     |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                       |
| Geometric mean | (ref)                                                        | 1.00x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 90.7 ms                                                      | 83.4 ms: 1.09x faster                                      |
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                       |
| float          | 74.2 ms                                                      | 79.1 ms: 1.07x slower                                      |
| Geometric mean | (ref)                                                        | 1.01x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 158 ms                                                       | 143 ms: 1.11x faster                                       |
| regex_v8       | 23.9 ms                                                      | 24.1 ms: 1.01x slower                                      |
| regex_effbot   | 3.50 ms                                                      | 3.53 ms: 1.01x slower                                      |
| regex_dna      | 227 ms                                                       | 244 ms: 1.07x slower                                       |
| Geometric mean | (ref)                                                        | 1.00x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                      |
| json_loads           | 28.7 us                                                      | 24.3 us: 1.18x faster                                      |
| unpickle_pure_python | 241 us                                                       | 206 us: 1.17x faster                                       |
| xml_etree_parse      | 158 ms                                                       | 147 ms: 1.07x faster                                       |
| tomli_loads          | 2.26 sec                                                     | 2.20 sec: 1.03x faster                                     |
| xml_etree_iterparse  | 104 ms                                                       | 103 ms: 1.02x faster                                       |
| pickle_pure_python   | 319 us                                                       | 325 us: 1.02x slower                                       |
| xml_etree_process    | 56.5 ms                                                      | 58.2 ms: 1.03x slower                                      |
| pickle_dict          | 30.8 us                                                      | 32.6 us: 1.06x slower                                      |
| pickle               | 9.64 us                                                      | 10.2 us: 1.06x slower                                      |
| xml_etree_generate   | 80.5 ms                                                      | 85.5 ms: 1.06x slower                                      |
| unpickle_list        | 4.53 us                                                      | 4.82 us: 1.06x slower                                      |
| unpickle             | 13.4 us                                                      | 14.5 us: 1.08x slower                                      |
| pickle_list          | 3.83 us                                                      | 4.43 us: 1.16x slower                                      |
| Geometric mean       | (ref)                                                        | 1.01x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                      |
| python_startup_no_site | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                      |
| Geometric mean         | (ref)                                                        | 1.10x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-pythonperf2-x86_64-python-3.12-3.12.0+-028f477 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 153 us: 3.42x faster                                       |
| asyncio_tcp              | 753 ms                                                       | 379 ms: 1.99x faster                                       |
| asyncio_tcp_ssl          | 3.08 sec                                                     | 1.57 sec: 1.96x faster                                     |
| generators               | 56.0 ms                                                      | 36.8 ms: 1.52x faster                                      |
| json_dumps               | 13.4 ms                                                      | 10.4 ms: 1.29x faster                                      |
| chaos                    | 80.9 ms                                                      | 64.2 ms: 1.26x faster                                      |
| fannkuch                 | 429 ms                                                       | 344 ms: 1.25x faster                                       |
| deltablue                | 4.00 ms                                                      | 3.26 ms: 1.22x faster                                      |
| coroutines               | 27.6 ms                                                      | 22.7 ms: 1.21x faster                                      |
| hexiom                   | 7.13 ms                                                      | 5.96 ms: 1.20x faster                                      |
| richards_super           | 61.0 ms                                                      | 51.2 ms: 1.19x faster                                      |
| json_loads               | 28.7 us                                                      | 24.3 us: 1.18x faster                                      |
| unpickle_pure_python     | 241 us                                                       | 206 us: 1.17x faster                                       |
| nqueens                  | 103 ms                                                       | 89.1 ms: 1.15x faster                                      |
| scimark_lu               | 115 ms                                                       | 101 ms: 1.13x faster                                       |
| async_tree_memoization   | 630 ms                                                       | 557 ms: 1.13x faster                                       |
| async_tree_none          | 519 ms                                                       | 463 ms: 1.12x faster                                       |
| comprehensions           | 24.6 us                                                      | 21.9 us: 1.12x faster                                      |
| go                       | 164 ms                                                       | 147 ms: 1.11x faster                                       |
| regex_compile            | 158 ms                                                       | 143 ms: 1.11x faster                                       |
| async_tree_io            | 1.17 sec                                                     | 1.06 sec: 1.10x faster                                     |
| sqlglot_parse            | 1.53 ms                                                      | 1.39 ms: 1.10x faster                                      |
| json                     | 5.65 ms                                                      | 5.16 ms: 1.10x faster                                      |
| nbody                    | 90.7 ms                                                      | 83.4 ms: 1.09x faster                                      |
| mako                     | 11.0 ms                                                      | 10.1 ms: 1.09x faster                                      |
| mdp                      | 2.75 sec                                                     | 2.54 sec: 1.08x faster                                     |
| logging_silent           | 101 ns                                                       | 93.6 ns: 1.08x faster                                      |
| richards                 | 48.3 ms                                                      | 45.1 ms: 1.07x faster                                      |
| xml_etree_parse          | 158 ms                                                       | 147 ms: 1.07x faster                                       |
| sqlglot_transpile        | 1.92 ms                                                      | 1.80 ms: 1.07x faster                                      |
| pycparser                | 1.32 sec                                                     | 1.25 sec: 1.06x faster                                     |
| async_tree_cpu_io_mixed  | 749 ms                                                       | 705 ms: 1.06x faster                                       |
| logging_format           | 8.11 us                                                      | 7.65 us: 1.06x faster                                      |
| sqlglot_normalize        | 126 ms                                                       | 119 ms: 1.06x faster                                       |
| bench_thread_pool        | 1.01 ms                                                      | 962 us: 1.05x faster                                       |
| raytrace                 | 317 ms                                                       | 301 ms: 1.05x faster                                       |
| deepcopy                 | 399 us                                                       | 381 us: 1.05x faster                                       |
| crypto_pyaes             | 83.4 ms                                                      | 79.8 ms: 1.05x faster                                      |
| dulwich_log              | 68.4 ms                                                      | 65.7 ms: 1.04x faster                                      |
| deepcopy_memo            | 38.8 us                                                      | 37.2 us: 1.04x faster                                      |
| dask                     | 410 ms                                                       | 396 ms: 1.04x faster                                       |
| tomli_loads              | 2.26 sec                                                     | 2.20 sec: 1.03x faster                                     |
| pyflate                  | 449 ms                                                       | 436 ms: 1.03x faster                                       |
| logging_simple           | 7.19 us                                                      | 7.00 us: 1.03x faster                                      |
| deepcopy_reduce          | 3.51 us                                                      | 3.44 us: 1.02x faster                                      |
| create_gc_cycles         | 1.61 ms                                                      | 1.58 ms: 1.02x faster                                      |
| spectral_norm            | 93.3 ms                                                      | 91.9 ms: 1.02x faster                                      |
| tornado_http             | 122 ms                                                       | 120 ms: 1.02x faster                                       |
| xml_etree_iterparse      | 104 ms                                                       | 103 ms: 1.02x faster                                       |
| scimark_sor              | 111 ms                                                       | 110 ms: 1.01x faster                                       |
| sqlglot_optimize         | 59.8 ms                                                      | 59.2 ms: 1.01x faster                                      |
| meteor_contest           | 131 ms                                                       | 130 ms: 1.00x faster                                       |
| 2to3                     | 288 ms                                                       | 287 ms: 1.00x faster                                       |
| regex_v8                 | 23.9 ms                                                      | 24.1 ms: 1.01x slower                                      |
| docutils                 | 2.86 sec                                                     | 2.87 sec: 1.01x slower                                     |
| pathlib                  | 19.1 ms                                                      | 19.2 ms: 1.01x slower                                      |
| regex_effbot             | 3.50 ms                                                      | 3.53 ms: 1.01x slower                                      |
| pickle_pure_python       | 319 us                                                       | 325 us: 1.02x slower                                       |
| pprint_pformat           | 1.63 sec                                                     | 1.66 sec: 1.02x slower                                     |
| scimark_monte_carlo      | 68.2 ms                                                      | 69.6 ms: 1.02x slower                                      |
| gc_traversal             | 3.85 ms                                                      | 3.94 ms: 1.02x slower                                      |
| xml_etree_process        | 56.5 ms                                                      | 58.2 ms: 1.03x slower                                      |
| pprint_safe_repr         | 784 ms                                                       | 817 ms: 1.04x slower                                       |
| pidigits                 | 251 ms                                                       | 264 ms: 1.05x slower                                       |
| pickle_dict              | 30.8 us                                                      | 32.6 us: 1.06x slower                                      |
| pickle                   | 9.64 us                                                      | 10.2 us: 1.06x slower                                      |
| xml_etree_generate       | 80.5 ms                                                      | 85.5 ms: 1.06x slower                                      |
| unpickle_list            | 4.53 us                                                      | 4.82 us: 1.06x slower                                      |
| float                    | 74.2 ms                                                      | 79.1 ms: 1.07x slower                                      |
| regex_dna                | 227 ms                                                       | 244 ms: 1.07x slower                                       |
| scimark_fft              | 285 ms                                                       | 306 ms: 1.07x slower                                       |
| scimark_sparse_mat_mult  | 4.05 ms                                                      | 4.36 ms: 1.08x slower                                      |
| unpickle                 | 13.4 us                                                      | 14.5 us: 1.08x slower                                      |
| telco                    | 6.86 ms                                                      | 7.45 ms: 1.09x slower                                      |
| coverage                 | 84.8 ms                                                      | 92.1 ms: 1.09x slower                                      |
| sqlite_synth             | 2.50 us                                                      | 2.72 us: 1.09x slower                                      |
| python_startup           | 10.8 ms                                                      | 11.7 ms: 1.09x slower                                      |
| python_startup_no_site   | 7.76 ms                                                      | 8.68 ms: 1.12x slower                                      |
| pickle_list              | 3.83 us                                                      | 4.43 us: 1.16x slower                                      |
| unpack_sequence          | 45.6 ns                                                      | 53.7 ns: 1.18x slower                                      |
| async_generators         | 316 ms                                                       | 385 ms: 1.22x slower                                       |
| bench_mp_pool            | 4.62 ms                                                      | 5.87 ms: 1.27x slower                                      |
| Geometric mean           | (ref)                                                        | 1.06x faster                                               |

Benchmark hidden because not significant (1): mypy2
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.94% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
