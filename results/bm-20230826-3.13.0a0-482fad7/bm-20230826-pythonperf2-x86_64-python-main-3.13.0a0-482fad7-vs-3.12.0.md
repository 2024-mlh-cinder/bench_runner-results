
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 482fad7
- commit date: 2023-08-26
- overall geometric mean: 1.02x slower
- HPT reliability: 99.27%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.90 sec: 1.00x slower                                      |
| Geometric mean | (ref)                                                        | 1.00x slower                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 85.1 ms: 1.11x faster                                       |
| pidigits       | 264 ms                                                       | 259 ms: 1.02x faster                                        |
| float          | 78.5 ms                                                      | 81.0 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                        | 1.03x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 249 ms: 1.04x slower                                        |
| regex_compile  | 146 ms                                                       | 151 ms: 1.04x slower                                        |
| regex_effbot   | 3.47 ms                                                      | 3.64 ms: 1.05x slower                                       |
| regex_v8       | 25.0 ms                                                      | 26.8 ms: 1.07x slower                                       |
| Geometric mean | (ref)                                                        | 1.05x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                      | 4.63 us: 1.03x faster                                       |
| unpickle             | 14.8 us                                                      | 14.4 us: 1.03x faster                                       |
| pickle_pure_python   | 323 us                                                       | 318 us: 1.02x faster                                        |
| json_dumps           | 10.2 ms                                                      | 10.3 ms: 1.00x slower                                       |
| pickle_list          | 4.39 us                                                      | 4.42 us: 1.01x slower                                       |
| xml_etree_generate   | 86.1 ms                                                      | 87.1 ms: 1.01x slower                                       |
| pickle_dict          | 31.7 us                                                      | 32.1 us: 1.01x slower                                       |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| xml_etree_process    | 58.3 ms                                                      | 59.6 ms: 1.02x slower                                       |
| tomli_loads          | 2.20 sec                                                     | 2.26 sec: 1.03x slower                                      |
| json_loads           | 24.3 us                                                      | 25.1 us: 1.03x slower                                       |
| xml_etree_iterparse  | 103 ms                                                       | 107 ms: 1.04x slower                                        |
| unpickle_pure_python | 207 us                                                       | 225 us: 1.09x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 11.6 ms: 1.01x faster                                       |
| python_startup_no_site | 8.70 ms                                                      | 8.66 ms: 1.00x faster                                       |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-pythonperf2-x86_64-python-main-3.13.0a0-482fad7 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.66 ms: 1.15x faster                                       |
| crypto_pyaes             | 80.9 ms                                                      | 72.5 ms: 1.12x faster                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 65.1 ms: 1.11x faster                                       |
| nbody                    | 94.1 ms                                                      | 85.1 ms: 1.11x faster                                       |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.05 ms: 1.09x faster                                       |
| coverage                 | 89.6 ms                                                      | 83.5 ms: 1.07x faster                                       |
| unpack_sequence          | 53.3 ns                                                      | 49.9 ns: 1.07x faster                                       |
| raytrace                 | 302 ms                                                       | 287 ms: 1.05x faster                                        |
| async_tree_none          | 459 ms                                                       | 440 ms: 1.04x faster                                        |
| asyncio_tcp              | 381 ms                                                       | 369 ms: 1.03x faster                                        |
| unpickle_list            | 4.77 us                                                      | 4.63 us: 1.03x faster                                       |
| unpickle                 | 14.8 us                                                      | 14.4 us: 1.03x faster                                       |
| create_gc_cycles         | 1.67 ms                                                      | 1.63 ms: 1.03x faster                                       |
| pidigits                 | 264 ms                                                       | 259 ms: 1.02x faster                                        |
| chaos                    | 62.9 ms                                                      | 61.9 ms: 1.02x faster                                       |
| pickle_pure_python       | 323 us                                                       | 318 us: 1.02x faster                                        |
| scimark_fft              | 304 ms                                                       | 299 ms: 1.02x faster                                        |
| coroutines               | 23.0 ms                                                      | 22.8 ms: 1.01x faster                                       |
| pathlib                  | 19.8 ms                                                      | 19.6 ms: 1.01x faster                                       |
| sqlglot_normalize        | 117 ms                                                       | 116 ms: 1.01x faster                                        |
| scimark_lu               | 101 ms                                                       | 99.9 ms: 1.01x faster                                       |
| typing_runtime_protocols | 151 us                                                       | 150 us: 1.01x faster                                        |
| deepcopy_reduce          | 3.46 us                                                      | 3.44 us: 1.01x faster                                       |
| python_startup           | 11.7 ms                                                      | 11.6 ms: 1.01x faster                                       |
| python_startup_no_site   | 8.70 ms                                                      | 8.66 ms: 1.00x faster                                       |
| generators               | 36.7 ms                                                      | 36.6 ms: 1.00x faster                                       |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                      |
| mdp                      | 2.53 sec                                                     | 2.54 sec: 1.00x slower                                      |
| json_dumps               | 10.2 ms                                                      | 10.3 ms: 1.00x slower                                       |
| docutils                 | 2.89 sec                                                     | 2.90 sec: 1.00x slower                                      |
| sqlite_synth             | 2.70 us                                                      | 2.71 us: 1.00x slower                                       |
| nqueens                  | 90.1 ms                                                      | 90.6 ms: 1.01x slower                                       |
| pickle_list              | 4.39 us                                                      | 4.42 us: 1.01x slower                                       |
| deepcopy_memo            | 37.4 us                                                      | 37.8 us: 1.01x slower                                       |
| xml_etree_generate       | 86.1 ms                                                      | 87.1 ms: 1.01x slower                                       |
| pickle_dict              | 31.7 us                                                      | 32.1 us: 1.01x slower                                       |
| sqlglot_optimize         | 57.8 ms                                                      | 58.5 ms: 1.01x slower                                       |
| sqlglot_parse            | 1.40 ms                                                      | 1.42 ms: 1.01x slower                                       |
| sqlglot_transpile        | 1.80 ms                                                      | 1.83 ms: 1.01x slower                                       |
| mypy2                    | 368 ms                                                       | 374 ms: 1.02x slower                                        |
| logging_format           | 7.37 us                                                      | 7.50 us: 1.02x slower                                       |
| logging_simple           | 6.73 us                                                      | 6.85 us: 1.02x slower                                       |
| xml_etree_parse          | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| xml_etree_process        | 58.3 ms                                                      | 59.6 ms: 1.02x slower                                       |
| async_generators         | 385 ms                                                       | 395 ms: 1.02x slower                                        |
| meteor_contest           | 128 ms                                                       | 131 ms: 1.03x slower                                        |
| deepcopy                 | 376 us                                                       | 386 us: 1.03x slower                                        |
| tomli_loads              | 2.20 sec                                                     | 2.26 sec: 1.03x slower                                      |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                      |
| float                    | 78.5 ms                                                      | 81.0 ms: 1.03x slower                                       |
| logging_silent           | 95.6 ns                                                      | 98.7 ns: 1.03x slower                                       |
| json_loads               | 24.3 us                                                      | 25.1 us: 1.03x slower                                       |
| comprehensions           | 21.9 us                                                      | 22.7 us: 1.04x slower                                       |
| regex_dna                | 241 ms                                                       | 249 ms: 1.04x slower                                        |
| xml_etree_iterparse      | 103 ms                                                       | 107 ms: 1.04x slower                                        |
| regex_compile            | 146 ms                                                       | 151 ms: 1.04x slower                                        |
| mako                     | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                       |
| regex_effbot             | 3.47 ms                                                      | 3.64 ms: 1.05x slower                                       |
| pycparser                | 1.27 sec                                                     | 1.34 sec: 1.05x slower                                      |
| dulwich_log              | 65.3 ms                                                      | 69.9 ms: 1.07x slower                                       |
| regex_v8                 | 25.0 ms                                                      | 26.8 ms: 1.07x slower                                       |
| unpickle_pure_python     | 207 us                                                       | 225 us: 1.09x slower                                        |
| hexiom                   | 5.96 ms                                                      | 6.53 ms: 1.10x slower                                       |
| fannkuch                 | 350 ms                                                       | 387 ms: 1.11x slower                                        |
| deltablue                | 3.29 ms                                                      | 3.68 ms: 1.12x slower                                       |
| go                       | 150 ms                                                       | 170 ms: 1.13x slower                                        |
| pyflate                  | 447 ms                                                       | 510 ms: 1.14x slower                                        |
| telco                    | 6.96 ms                                                      | 8.12 ms: 1.17x slower                                       |
| richards_super           | 51.7 ms                                                      | 60.3 ms: 1.17x slower                                       |
| richards                 | 45.0 ms                                                      | 54.6 ms: 1.21x slower                                       |
| scimark_sor              | 110 ms                                                       | 147 ms: 1.34x slower                                        |
| dask                     | 397 ms                                                       | 591 ms: 1.49x slower                                        |
| Geometric mean           | (ref)                                                        | 1.02x slower                                                |

Benchmark hidden because not significant (10): json, pickle, tornado_http, async_tree_cpu_io_mixed, pprint_safe_repr, pprint_pformat, spectral_norm, async_tree_memoization, gc_traversal, bench_thread_pool
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 99.27% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
