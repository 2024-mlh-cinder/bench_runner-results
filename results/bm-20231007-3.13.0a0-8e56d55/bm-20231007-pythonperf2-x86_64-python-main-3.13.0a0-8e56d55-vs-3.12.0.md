
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 8e56d55
- commit date: 2023-10-07
- overall geometric mean: 1.01x slower
- HPT reliability: 81.39%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.86 sec: 1.01x faster                                      |
| Geometric mean | (ref)                                                        | 1.00x faster                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 85.1 ms: 1.11x faster                                       |
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                        |
| float          | 78.5 ms                                                      | 80.7 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 235 ms: 1.02x faster                                        |
| regex_effbot   | 3.47 ms                                                      | 3.44 ms: 1.01x faster                                       |
| regex_v8       | 25.0 ms                                                      | 25.1 ms: 1.00x slower                                       |
| regex_compile  | 146 ms                                                       | 148 ms: 1.02x slower                                        |
| Geometric mean | (ref)                                                        | 1.00x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 323 us                                                       | 311 us: 1.04x faster                                        |
| unpickle             | 14.8 us                                                      | 14.3 us: 1.04x faster                                       |
| unpickle_list        | 4.77 us                                                      | 4.68 us: 1.02x faster                                       |
| pickle_dict          | 31.7 us                                                      | 31.6 us: 1.00x faster                                       |
| xml_etree_process    | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                       |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| pickle               | 10.1 us                                                      | 10.3 us: 1.02x slower                                       |
| json_dumps           | 10.2 ms                                                      | 10.5 ms: 1.02x slower                                       |
| json_loads           | 24.3 us                                                      | 25.0 us: 1.03x slower                                       |
| xml_etree_iterparse  | 103 ms                                                       | 107 ms: 1.04x slower                                        |
| tomli_loads          | 2.20 sec                                                     | 2.32 sec: 1.06x slower                                      |
| unpickle_pure_python | 207 us                                                       | 226 us: 1.09x slower                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                |

Benchmark hidden because not significant (2): pickle_list, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                       |
| python_startup         | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                       |
| Geometric mean         | (ref)                                                        | 1.04x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.4 ms: 1.05x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf2-x86_64-python-main-3.13.0a0-8e56d55 |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| unpack_sequence          | 53.3 ns                                                      | 44.8 ns: 1.19x faster                                       |
| bench_mp_pool            | 5.34 ms                                                      | 4.57 ms: 1.17x faster                                       |
| raytrace                 | 302 ms                                                       | 268 ms: 1.13x faster                                        |
| crypto_pyaes             | 80.9 ms                                                      | 72.9 ms: 1.11x faster                                       |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.00 ms: 1.11x faster                                       |
| nbody                    | 94.1 ms                                                      | 85.1 ms: 1.11x faster                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 66.8 ms: 1.08x faster                                       |
| coverage                 | 89.6 ms                                                      | 82.8 ms: 1.08x faster                                       |
| async_tree_none          | 459 ms                                                       | 435 ms: 1.06x faster                                        |
| generators               | 36.7 ms                                                      | 34.8 ms: 1.05x faster                                       |
| asyncio_tcp              | 381 ms                                                       | 366 ms: 1.04x faster                                        |
| pickle_pure_python       | 323 us                                                       | 311 us: 1.04x faster                                        |
| unpickle                 | 14.8 us                                                      | 14.3 us: 1.04x faster                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.34 us: 1.03x faster                                       |
| chaos                    | 62.9 ms                                                      | 61.1 ms: 1.03x faster                                       |
| scimark_fft              | 304 ms                                                       | 296 ms: 1.03x faster                                        |
| nqueens                  | 90.1 ms                                                      | 87.9 ms: 1.03x faster                                       |
| regex_dna                | 241 ms                                                       | 235 ms: 1.02x faster                                        |
| deepcopy                 | 376 us                                                       | 368 us: 1.02x faster                                        |
| unpickle_list            | 4.77 us                                                      | 4.68 us: 1.02x faster                                       |
| sqlglot_normalize        | 117 ms                                                       | 115 ms: 1.02x faster                                        |
| pprint_safe_repr         | 823 ms                                                       | 808 ms: 1.02x faster                                        |
| pprint_pformat           | 1.67 sec                                                     | 1.65 sec: 1.02x faster                                      |
| deepcopy_memo            | 37.4 us                                                      | 36.9 us: 1.01x faster                                       |
| typing_runtime_protocols | 151 us                                                       | 150 us: 1.01x faster                                        |
| regex_effbot             | 3.47 ms                                                      | 3.44 ms: 1.01x faster                                       |
| docutils                 | 2.89 sec                                                     | 2.86 sec: 1.01x faster                                      |
| mdp                      | 2.53 sec                                                     | 2.51 sec: 1.01x faster                                      |
| pathlib                  | 19.8 ms                                                      | 19.6 ms: 1.01x faster                                       |
| spectral_norm            | 91.6 ms                                                      | 91.0 ms: 1.01x faster                                       |
| pickle_dict              | 31.7 us                                                      | 31.6 us: 1.00x faster                                       |
| python_startup_no_site   | 8.70 ms                                                      | 8.67 ms: 1.00x faster                                       |
| regex_v8                 | 25.0 ms                                                      | 25.1 ms: 1.00x slower                                       |
| pidigits                 | 264 ms                                                       | 265 ms: 1.00x slower                                        |
| mypy2                    | 368 ms                                                       | 370 ms: 1.00x slower                                        |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                      |
| sqlglot_optimize         | 57.8 ms                                                      | 58.2 ms: 1.01x slower                                       |
| comprehensions           | 21.9 us                                                      | 22.1 us: 1.01x slower                                       |
| coroutines               | 23.0 ms                                                      | 23.3 ms: 1.01x slower                                       |
| logging_silent           | 95.6 ns                                                      | 96.9 ns: 1.01x slower                                       |
| sqlglot_parse            | 1.40 ms                                                      | 1.42 ms: 1.01x slower                                       |
| xml_etree_process        | 58.3 ms                                                      | 59.1 ms: 1.01x slower                                       |
| sqlglot_transpile        | 1.80 ms                                                      | 1.83 ms: 1.02x slower                                       |
| xml_etree_parse          | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| regex_compile            | 146 ms                                                       | 148 ms: 1.02x slower                                        |
| pickle                   | 10.1 us                                                      | 10.3 us: 1.02x slower                                       |
| logging_simple           | 6.73 us                                                      | 6.88 us: 1.02x slower                                       |
| json_dumps               | 10.2 ms                                                      | 10.5 ms: 1.02x slower                                       |
| async_tree_io            | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                      |
| logging_format           | 7.37 us                                                      | 7.56 us: 1.03x slower                                       |
| float                    | 78.5 ms                                                      | 80.7 ms: 1.03x slower                                       |
| meteor_contest           | 128 ms                                                       | 132 ms: 1.03x slower                                        |
| json_loads               | 24.3 us                                                      | 25.0 us: 1.03x slower                                       |
| xml_etree_iterparse      | 103 ms                                                       | 107 ms: 1.04x slower                                        |
| async_generators         | 385 ms                                                       | 404 ms: 1.05x slower                                        |
| mako                     | 9.94 ms                                                      | 10.4 ms: 1.05x slower                                       |
| gc_traversal             | 3.54 ms                                                      | 3.74 ms: 1.05x slower                                       |
| tomli_loads              | 2.20 sec                                                     | 2.32 sec: 1.06x slower                                      |
| dulwich_log              | 65.3 ms                                                      | 69.4 ms: 1.06x slower                                       |
| python_startup           | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                       |
| hexiom                   | 5.96 ms                                                      | 6.50 ms: 1.09x slower                                       |
| unpickle_pure_python     | 207 us                                                       | 226 us: 1.09x slower                                        |
| deltablue                | 3.29 ms                                                      | 3.61 ms: 1.10x slower                                       |
| fannkuch                 | 350 ms                                                       | 385 ms: 1.10x slower                                        |
| go                       | 150 ms                                                       | 171 ms: 1.14x slower                                        |
| pyflate                  | 447 ms                                                       | 514 ms: 1.15x slower                                        |
| telco                    | 6.96 ms                                                      | 8.08 ms: 1.16x slower                                       |
| richards_super           | 51.7 ms                                                      | 60.2 ms: 1.16x slower                                       |
| richards                 | 45.0 ms                                                      | 54.0 ms: 1.20x slower                                       |
| scimark_sor              | 110 ms                                                       | 146 ms: 1.32x slower                                        |
| Geometric mean           | (ref)                                                        | 1.01x slower                                                |

Benchmark hidden because not significant (11): bench_thread_pool, async_tree_cpu_io_mixed, async_tree_memoization, create_gc_cycles, json, scimark_lu, sqlite_synth, pickle_list, xml_etree_generate, tornado_http, pycparser
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 81.39% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
