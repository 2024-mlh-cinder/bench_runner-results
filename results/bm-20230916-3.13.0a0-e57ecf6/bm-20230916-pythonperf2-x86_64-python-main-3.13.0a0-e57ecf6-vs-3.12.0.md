
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.02x slower
- HPT reliability: 98.98%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                      |
| Geometric mean | (ref)                                                        | 1.01x faster                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 86.2 ms: 1.09x faster                                       |
| float          | 78.5 ms                                                      | 80.0 ms: 1.02x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 245 ms: 1.02x slower                                        |
| regex_v8       | 25.0 ms                                                      | 25.5 ms: 1.02x slower                                       |
| regex_compile  | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| regex_effbot   | 3.47 ms                                                      | 3.61 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                      | 4.67 us: 1.02x faster                                       |
| pickle_pure_python   | 323 us                                                       | 317 us: 1.02x faster                                        |
| unpickle             | 14.8 us                                                      | 14.6 us: 1.01x faster                                       |
| xml_etree_process    | 58.3 ms                                                      | 58.7 ms: 1.01x slower                                       |
| tomli_loads          | 2.20 sec                                                     | 2.22 sec: 1.01x slower                                      |
| xml_etree_parse      | 146 ms                                                       | 150 ms: 1.02x slower                                        |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.02x slower                                        |
| pickle_dict          | 31.7 us                                                      | 32.6 us: 1.03x slower                                       |
| json_loads           | 24.3 us                                                      | 24.9 us: 1.03x slower                                       |
| json_dumps           | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                       |
| unpickle_pure_python | 207 us                                                       | 221 us: 1.07x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                |

Benchmark hidden because not significant (3): pickle_list, xml_etree_generate, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                       |
| python_startup         | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                       |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230916-pythonperf2-x86_64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.55 ms: 1.17x faster                                       |
| unpack_sequence          | 53.3 ns                                                      | 46.2 ns: 1.15x faster                                       |
| raytrace                 | 302 ms                                                       | 270 ms: 1.12x faster                                        |
| crypto_pyaes             | 80.9 ms                                                      | 73.5 ms: 1.10x faster                                       |
| coverage                 | 89.6 ms                                                      | 81.5 ms: 1.10x faster                                       |
| nbody                    | 94.1 ms                                                      | 86.2 ms: 1.09x faster                                       |
| generators               | 36.7 ms                                                      | 34.7 ms: 1.06x faster                                       |
| async_tree_none          | 459 ms                                                       | 436 ms: 1.05x faster                                        |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.24 ms: 1.04x faster                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 70.1 ms: 1.03x faster                                       |
| asyncio_tcp              | 381 ms                                                       | 371 ms: 1.03x faster                                        |
| scimark_fft              | 304 ms                                                       | 298 ms: 1.02x faster                                        |
| unpickle_list            | 4.77 us                                                      | 4.67 us: 1.02x faster                                       |
| pickle_pure_python       | 323 us                                                       | 317 us: 1.02x faster                                        |
| unpickle                 | 14.8 us                                                      | 14.6 us: 1.01x faster                                       |
| chaos                    | 62.9 ms                                                      | 62.1 ms: 1.01x faster                                       |
| sqlglot_normalize        | 117 ms                                                       | 116 ms: 1.01x faster                                        |
| nqueens                  | 90.1 ms                                                      | 89.5 ms: 1.01x faster                                       |
| typing_runtime_protocols | 151 us                                                       | 150 us: 1.01x faster                                        |
| docutils                 | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                      |
| spectral_norm            | 91.6 ms                                                      | 91.2 ms: 1.00x faster                                       |
| pathlib                  | 19.8 ms                                                      | 19.7 ms: 1.00x faster                                       |
| python_startup_no_site   | 8.70 ms                                                      | 8.68 ms: 1.00x faster                                       |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                      |
| mypy2                    | 368 ms                                                       | 370 ms: 1.00x slower                                        |
| mdp                      | 2.53 sec                                                     | 2.55 sec: 1.01x slower                                      |
| xml_etree_process        | 58.3 ms                                                      | 58.7 ms: 1.01x slower                                       |
| sqlglot_transpile        | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                       |
| tomli_loads              | 2.20 sec                                                     | 2.22 sec: 1.01x slower                                      |
| pycparser                | 1.27 sec                                                     | 1.29 sec: 1.01x slower                                      |
| sqlglot_optimize         | 57.8 ms                                                      | 58.7 ms: 1.01x slower                                       |
| scimark_lu               | 101 ms                                                       | 102 ms: 1.02x slower                                        |
| regex_dna                | 241 ms                                                       | 245 ms: 1.02x slower                                        |
| float                    | 78.5 ms                                                      | 80.0 ms: 1.02x slower                                       |
| regex_v8                 | 25.0 ms                                                      | 25.5 ms: 1.02x slower                                       |
| regex_compile            | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| logging_silent           | 95.6 ns                                                      | 97.7 ns: 1.02x slower                                       |
| async_generators         | 385 ms                                                       | 393 ms: 1.02x slower                                        |
| deepcopy                 | 376 us                                                       | 384 us: 1.02x slower                                        |
| deepcopy_memo            | 37.4 us                                                      | 38.3 us: 1.02x slower                                       |
| meteor_contest           | 128 ms                                                       | 131 ms: 1.02x slower                                        |
| xml_etree_parse          | 146 ms                                                       | 150 ms: 1.02x slower                                        |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.02x slower                                        |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                      |
| pickle_dict              | 31.7 us                                                      | 32.6 us: 1.03x slower                                       |
| json_loads               | 24.3 us                                                      | 24.9 us: 1.03x slower                                       |
| logging_simple           | 6.73 us                                                      | 6.95 us: 1.03x slower                                       |
| logging_format           | 7.37 us                                                      | 7.61 us: 1.03x slower                                       |
| json_dumps               | 10.2 ms                                                      | 10.6 ms: 1.04x slower                                       |
| mako                     | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                       |
| regex_effbot             | 3.47 ms                                                      | 3.61 ms: 1.04x slower                                       |
| dulwich_log              | 65.3 ms                                                      | 68.7 ms: 1.05x slower                                       |
| unpickle_pure_python     | 207 us                                                       | 221 us: 1.07x slower                                        |
| python_startup           | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                       |
| gc_traversal             | 3.54 ms                                                      | 3.83 ms: 1.08x slower                                       |
| hexiom                   | 5.96 ms                                                      | 6.50 ms: 1.09x slower                                       |
| deltablue                | 3.29 ms                                                      | 3.66 ms: 1.11x slower                                       |
| go                       | 150 ms                                                       | 170 ms: 1.13x slower                                        |
| pyflate                  | 447 ms                                                       | 516 ms: 1.15x slower                                        |
| fannkuch                 | 350 ms                                                       | 405 ms: 1.16x slower                                        |
| telco                    | 6.96 ms                                                      | 8.11 ms: 1.16x slower                                       |
| richards_super           | 51.7 ms                                                      | 63.3 ms: 1.22x slower                                       |
| richards                 | 45.0 ms                                                      | 57.6 ms: 1.28x slower                                       |
| scimark_sor              | 110 ms                                                       | 150 ms: 1.36x slower                                        |
| dask                     | 397 ms                                                       | 589 ms: 1.49x slower                                        |
| Geometric mean           | (ref)                                                        | 1.02x slower                                                |

Benchmark hidden because not significant (17): bench_thread_pool, tornado_http, async_tree_cpu_io_mixed, pickle_list, async_tree_memoization, xml_etree_generate, comprehensions, sqlite_synth, pprint_pformat, pidigits, sqlglot_parse, json, deepcopy_reduce, pprint_safe_repr, pickle, coroutines, create_gc_cycles
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 98.98% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
