
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.02x slower
- HPT reliability: 98.93%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.90 sec: 1.01x slower                                       |
| Geometric mean | (ref)                                                        | 1.00x slower                                                 |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 86.2 ms: 1.09x faster                                        |
| float          | 78.5 ms                                                      | 78.0 ms: 1.01x faster                                        |
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                         |
| Geometric mean | (ref)                                                        | 1.03x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 24.5 ms: 1.02x faster                                        |
| regex_dna      | 241 ms                                                       | 238 ms: 1.01x faster                                         |
| regex_compile  | 146 ms                                                       | 148 ms: 1.01x slower                                         |
| regex_effbot   | 3.47 ms                                                      | 3.53 ms: 1.02x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                      | 4.47 us: 1.07x faster                                        |
| unpickle             | 14.8 us                                                      | 14.2 us: 1.04x faster                                        |
| pickle_pure_python   | 323 us                                                       | 313 us: 1.03x faster                                         |
| xml_etree_process    | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                        |
| pickle_dict          | 31.7 us                                                      | 32.3 us: 1.02x slower                                        |
| xml_etree_parse      | 146 ms                                                       | 150 ms: 1.03x slower                                         |
| json_dumps           | 10.2 ms                                                      | 10.5 ms: 1.03x slower                                        |
| xml_etree_iterparse  | 103 ms                                                       | 107 ms: 1.04x slower                                         |
| tomli_loads          | 2.20 sec                                                     | 2.32 sec: 1.05x slower                                       |
| unpickle_pure_python | 207 us                                                       | 225 us: 1.09x slower                                         |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                 |

Benchmark hidden because not significant (4): pickle_list, pickle, xml_etree_generate, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                        |
| Geometric mean | (ref)                                                        | 1.04x slower                                                 |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.4 ms: 1.04x slower                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf2-x86_64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.64 ms: 1.15x faster                                        |
| crypto_pyaes             | 80.9 ms                                                      | 71.7 ms: 1.13x faster                                        |
| coverage                 | 89.6 ms                                                      | 80.2 ms: 1.12x faster                                        |
| nbody                    | 94.1 ms                                                      | 86.2 ms: 1.09x faster                                        |
| create_gc_cycles         | 1.67 ms                                                      | 1.54 ms: 1.09x faster                                        |
| raytrace                 | 302 ms                                                       | 280 ms: 1.08x faster                                         |
| unpickle_list            | 4.77 us                                                      | 4.47 us: 1.07x faster                                        |
| async_tree_none          | 459 ms                                                       | 434 ms: 1.06x faster                                         |
| unpickle                 | 14.8 us                                                      | 14.2 us: 1.04x faster                                        |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.28 ms: 1.03x faster                                        |
| pickle_pure_python       | 323 us                                                       | 313 us: 1.03x faster                                         |
| deepcopy_reduce          | 3.46 us                                                      | 3.36 us: 1.03x faster                                        |
| asyncio_tcp              | 381 ms                                                       | 371 ms: 1.03x faster                                         |
| scimark_monte_carlo      | 72.4 ms                                                      | 70.6 ms: 1.02x faster                                        |
| generators               | 36.7 ms                                                      | 35.8 ms: 1.02x faster                                        |
| nqueens                  | 90.1 ms                                                      | 88.3 ms: 1.02x faster                                        |
| regex_v8                 | 25.0 ms                                                      | 24.5 ms: 1.02x faster                                        |
| coroutines               | 23.0 ms                                                      | 22.7 ms: 1.01x faster                                        |
| json                     | 5.14 ms                                                      | 5.08 ms: 1.01x faster                                        |
| comprehensions           | 21.9 us                                                      | 21.7 us: 1.01x faster                                        |
| sqlite_synth             | 2.70 us                                                      | 2.67 us: 1.01x faster                                        |
| regex_dna                | 241 ms                                                       | 238 ms: 1.01x faster                                         |
| async_tree_memoization   | 553 ms                                                       | 548 ms: 1.01x faster                                         |
| scimark_lu               | 101 ms                                                       | 99.7 ms: 1.01x faster                                        |
| float                    | 78.5 ms                                                      | 78.0 ms: 1.01x faster                                        |
| mdp                      | 2.53 sec                                                     | 2.52 sec: 1.01x faster                                       |
| pathlib                  | 19.8 ms                                                      | 19.7 ms: 1.00x faster                                        |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                       |
| deepcopy                 | 376 us                                                       | 377 us: 1.00x slower                                         |
| pidigits                 | 264 ms                                                       | 265 ms: 1.00x slower                                         |
| docutils                 | 2.89 sec                                                     | 2.90 sec: 1.01x slower                                       |
| chaos                    | 62.9 ms                                                      | 63.3 ms: 1.01x slower                                        |
| logging_format           | 7.37 us                                                      | 7.42 us: 1.01x slower                                        |
| sqlglot_parse            | 1.40 ms                                                      | 1.42 ms: 1.01x slower                                        |
| logging_simple           | 6.73 us                                                      | 6.81 us: 1.01x slower                                        |
| mypy2                    | 368 ms                                                       | 373 ms: 1.01x slower                                         |
| regex_compile            | 146 ms                                                       | 148 ms: 1.01x slower                                         |
| xml_etree_process        | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                        |
| sqlglot_transpile        | 1.80 ms                                                      | 1.83 ms: 1.01x slower                                        |
| meteor_contest           | 128 ms                                                       | 130 ms: 1.02x slower                                         |
| regex_effbot             | 3.47 ms                                                      | 3.53 ms: 1.02x slower                                        |
| pickle_dict              | 31.7 us                                                      | 32.3 us: 1.02x slower                                        |
| async_tree_io            | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                       |
| deepcopy_memo            | 37.4 us                                                      | 38.3 us: 1.02x slower                                        |
| sqlglot_optimize         | 57.8 ms                                                      | 59.2 ms: 1.02x slower                                        |
| xml_etree_parse          | 146 ms                                                       | 150 ms: 1.03x slower                                         |
| pprint_safe_repr         | 823 ms                                                       | 845 ms: 1.03x slower                                         |
| json_dumps               | 10.2 ms                                                      | 10.5 ms: 1.03x slower                                        |
| logging_silent           | 95.6 ns                                                      | 98.3 ns: 1.03x slower                                        |
| typing_runtime_protocols | 151 us                                                       | 156 us: 1.03x slower                                         |
| async_generators         | 385 ms                                                       | 397 ms: 1.03x slower                                         |
| unpack_sequence          | 53.3 ns                                                      | 54.9 ns: 1.03x slower                                        |
| pprint_pformat           | 1.67 sec                                                     | 1.73 sec: 1.03x slower                                       |
| xml_etree_iterparse      | 103 ms                                                       | 107 ms: 1.04x slower                                         |
| scimark_fft              | 304 ms                                                       | 316 ms: 1.04x slower                                         |
| pycparser                | 1.27 sec                                                     | 1.33 sec: 1.04x slower                                       |
| mako                     | 9.94 ms                                                      | 10.4 ms: 1.04x slower                                        |
| gc_traversal             | 3.54 ms                                                      | 3.72 ms: 1.05x slower                                        |
| tomli_loads              | 2.20 sec                                                     | 2.32 sec: 1.05x slower                                       |
| dulwich_log              | 65.3 ms                                                      | 69.4 ms: 1.06x slower                                        |
| python_startup           | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                        |
| hexiom                   | 5.96 ms                                                      | 6.46 ms: 1.08x slower                                        |
| unpickle_pure_python     | 207 us                                                       | 225 us: 1.09x slower                                         |
| deltablue                | 3.29 ms                                                      | 3.66 ms: 1.11x slower                                        |
| fannkuch                 | 350 ms                                                       | 392 ms: 1.12x slower                                         |
| go                       | 150 ms                                                       | 173 ms: 1.15x slower                                         |
| telco                    | 6.96 ms                                                      | 8.20 ms: 1.18x slower                                        |
| pyflate                  | 447 ms                                                       | 528 ms: 1.18x slower                                         |
| richards_super           | 51.7 ms                                                      | 61.3 ms: 1.19x slower                                        |
| richards                 | 45.0 ms                                                      | 55.7 ms: 1.24x slower                                        |
| scimark_sor              | 110 ms                                                       | 149 ms: 1.35x slower                                         |
| Geometric mean           | (ref)                                                        | 1.02x slower                                                 |

Benchmark hidden because not significant (10): bench_thread_pool, async_tree_cpu_io_mixed, pickle_list, pickle, xml_etree_generate, python_startup_no_site, sqlglot_normalize, spectral_norm, tornado_http, json_loads
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 98.93% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
