
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.02x slower
- HPT reliability: 91.69%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 85.7 ms: 1.10x faster                                       |
| pidigits       | 264 ms                                                       | 265 ms: 1.00x slower                                        |
| float          | 78.5 ms                                                      | 80.4 ms: 1.02x slower                                       |
| Geometric mean | (ref)                                                        | 1.02x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 146 ms                                                       | 148 ms: 1.02x slower                                        |
| regex_dna      | 241 ms                                                       | 248 ms: 1.03x slower                                        |
| regex_v8       | 25.0 ms                                                      | 25.9 ms: 1.04x slower                                       |
| regex_effbot   | 3.47 ms                                                      | 3.68 ms: 1.06x slower                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|----------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 323 us                                                       | 309 us: 1.05x faster                                        |
| xml_etree_process    | 58.3 ms                                                      | 57.9 ms: 1.01x faster                                       |
| xml_etree_generate   | 86.1 ms                                                      | 85.7 ms: 1.01x faster                                       |
| unpickle_list        | 4.77 us                                                      | 4.80 us: 1.01x slower                                       |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                       |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| tomli_loads          | 2.20 sec                                                     | 2.25 sec: 1.02x slower                                      |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.02x slower                                        |
| pickle_list          | 4.39 us                                                      | 4.50 us: 1.03x slower                                       |
| unpickle             | 14.8 us                                                      | 15.2 us: 1.03x slower                                       |
| json_loads           | 24.3 us                                                      | 25.6 us: 1.06x slower                                       |
| unpickle_pure_python | 207 us                                                       | 225 us: 1.09x slower                                        |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                |

Benchmark hidden because not significant (2): pickle, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 11.9 ms: 1.01x slower                                       |
| python_startup_no_site | 8.70 ms                                                      | 8.86 ms: 1.02x slower                                       |
| Geometric mean         | (ref)                                                        | 1.02x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|-----------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.2 ms: 1.03x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-pythonperf2-x86_64-python-main-3.13.0a0-a52213b |
|--------------------------|:------------------------------------------------------------:|:-----------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.68 ms: 1.14x faster                                       |
| crypto_pyaes             | 80.9 ms                                                      | 71.7 ms: 1.13x faster                                       |
| raytrace                 | 302 ms                                                       | 271 ms: 1.11x faster                                        |
| nbody                    | 94.1 ms                                                      | 85.7 ms: 1.10x faster                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 66.8 ms: 1.08x faster                                       |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.16 ms: 1.06x faster                                       |
| coverage                 | 89.6 ms                                                      | 84.3 ms: 1.06x faster                                       |
| async_tree_none          | 459 ms                                                       | 436 ms: 1.05x faster                                        |
| pickle_pure_python       | 323 us                                                       | 309 us: 1.05x faster                                        |
| generators               | 36.7 ms                                                      | 35.3 ms: 1.04x faster                                       |
| create_gc_cycles         | 1.67 ms                                                      | 1.62 ms: 1.04x faster                                       |
| asyncio_tcp              | 381 ms                                                       | 370 ms: 1.03x faster                                        |
| chaos                    | 62.9 ms                                                      | 61.2 ms: 1.03x faster                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.38 us: 1.02x faster                                       |
| pprint_safe_repr         | 823 ms                                                       | 805 ms: 1.02x faster                                        |
| scimark_lu               | 101 ms                                                       | 98.6 ms: 1.02x faster                                       |
| sqlglot_normalize        | 117 ms                                                       | 115 ms: 1.02x faster                                        |
| pprint_pformat           | 1.67 sec                                                     | 1.65 sec: 1.02x faster                                      |
| spectral_norm            | 91.6 ms                                                      | 90.3 ms: 1.01x faster                                       |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 696 ms: 1.01x faster                                        |
| async_tree_memoization   | 553 ms                                                       | 547 ms: 1.01x faster                                        |
| typing_runtime_protocols | 151 us                                                       | 149 us: 1.01x faster                                        |
| scimark_fft              | 304 ms                                                       | 301 ms: 1.01x faster                                        |
| deepcopy                 | 376 us                                                       | 373 us: 1.01x faster                                        |
| deepcopy_memo            | 37.4 us                                                      | 37.2 us: 1.01x faster                                       |
| xml_etree_process        | 58.3 ms                                                      | 57.9 ms: 1.01x faster                                       |
| unpack_sequence          | 53.3 ns                                                      | 53.0 ns: 1.01x faster                                       |
| xml_etree_generate       | 86.1 ms                                                      | 85.7 ms: 1.01x faster                                       |
| nqueens                  | 90.1 ms                                                      | 89.7 ms: 1.00x faster                                       |
| pathlib                  | 19.8 ms                                                      | 19.7 ms: 1.00x faster                                       |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                      |
| mdp                      | 2.53 sec                                                     | 2.54 sec: 1.00x slower                                      |
| pidigits                 | 264 ms                                                       | 265 ms: 1.00x slower                                        |
| unpickle_list            | 4.77 us                                                      | 4.80 us: 1.01x slower                                       |
| mypy2                    | 368 ms                                                       | 371 ms: 1.01x slower                                        |
| logging_format           | 7.37 us                                                      | 7.43 us: 1.01x slower                                       |
| sqlglot_parse            | 1.40 ms                                                      | 1.42 ms: 1.01x slower                                       |
| sqlglot_transpile        | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                       |
| meteor_contest           | 128 ms                                                       | 129 ms: 1.01x slower                                        |
| comprehensions           | 21.9 us                                                      | 22.2 us: 1.01x slower                                       |
| python_startup           | 11.7 ms                                                      | 11.9 ms: 1.01x slower                                       |
| pycparser                | 1.27 sec                                                     | 1.29 sec: 1.01x slower                                      |
| sqlglot_optimize         | 57.8 ms                                                      | 58.6 ms: 1.01x slower                                       |
| json_dumps               | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                       |
| coroutines               | 23.0 ms                                                      | 23.4 ms: 1.02x slower                                       |
| regex_compile            | 146 ms                                                       | 148 ms: 1.02x slower                                        |
| logging_simple           | 6.73 us                                                      | 6.85 us: 1.02x slower                                       |
| xml_etree_parse          | 146 ms                                                       | 149 ms: 1.02x slower                                        |
| python_startup_no_site   | 8.70 ms                                                      | 8.86 ms: 1.02x slower                                       |
| async_tree_io            | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                      |
| tomli_loads              | 2.20 sec                                                     | 2.25 sec: 1.02x slower                                      |
| float                    | 78.5 ms                                                      | 80.4 ms: 1.02x slower                                       |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.02x slower                                        |
| pickle_list              | 4.39 us                                                      | 4.50 us: 1.03x slower                                       |
| async_generators         | 385 ms                                                       | 395 ms: 1.03x slower                                        |
| logging_silent           | 95.6 ns                                                      | 98.2 ns: 1.03x slower                                       |
| mako                     | 9.94 ms                                                      | 10.2 ms: 1.03x slower                                       |
| unpickle                 | 14.8 us                                                      | 15.2 us: 1.03x slower                                       |
| regex_dna                | 241 ms                                                       | 248 ms: 1.03x slower                                        |
| regex_v8                 | 25.0 ms                                                      | 25.9 ms: 1.04x slower                                       |
| json_loads               | 24.3 us                                                      | 25.6 us: 1.06x slower                                       |
| regex_effbot             | 3.47 ms                                                      | 3.68 ms: 1.06x slower                                       |
| dulwich_log              | 65.3 ms                                                      | 69.6 ms: 1.07x slower                                       |
| hexiom                   | 5.96 ms                                                      | 6.44 ms: 1.08x slower                                       |
| unpickle_pure_python     | 207 us                                                       | 225 us: 1.09x slower                                        |
| fannkuch                 | 350 ms                                                       | 385 ms: 1.10x slower                                        |
| deltablue                | 3.29 ms                                                      | 3.66 ms: 1.11x slower                                       |
| pyflate                  | 447 ms                                                       | 504 ms: 1.13x slower                                        |
| go                       | 150 ms                                                       | 170 ms: 1.13x slower                                        |
| telco                    | 6.96 ms                                                      | 8.09 ms: 1.16x slower                                       |
| richards_super           | 51.7 ms                                                      | 60.3 ms: 1.17x slower                                       |
| richards                 | 45.0 ms                                                      | 54.2 ms: 1.20x slower                                       |
| scimark_sor              | 110 ms                                                       | 145 ms: 1.32x slower                                        |
| dask                     | 397 ms                                                       | 586 ms: 1.48x slower                                        |
| Geometric mean           | (ref)                                                        | 1.02x slower                                                |

Benchmark hidden because not significant (8): tornado_http, bench_thread_pool, gc_traversal, sqlite_synth, docutils, pickle, pickle_dict, json
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 91.69% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
