
# Results vs. 3.12.0

- fork: python
- ref: 2ac103c346ffe9d0e4c1
- machine: linux-x86_64
- commit hash: 2ac103c
- commit date: 2023-08-07
- overall geometric mean: 1.03x slower
- HPT reliability: 99.93%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230807-pythonperf2-x86_64-python-2ac103c346ffe9d0e4c1-3.13.0a0-2ac103c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.92 sec: 1.01x slower                                                      |
| Geometric mean | (ref)                                                        | 1.00x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230807-pythonperf2-x86_64-python-2ac103c346ffe9d0e4c1-3.13.0a0-2ac103c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 89.1 ms: 1.06x faster                                                       |
| pidigits       | 264 ms                                                       | 260 ms: 1.02x faster                                                        |
| float          | 78.5 ms                                                      | 81.3 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230807-pythonperf2-x86_64-python-2ac103c346ffe9d0e4c1-3.13.0a0-2ac103c |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 24.0 ms: 1.04x faster                                                       |
| regex_compile  | 146 ms                                                       | 151 ms: 1.03x slower                                                        |
| regex_dna      | 241 ms                                                       | 252 ms: 1.05x slower                                                        |
| regex_effbot   | 3.47 ms                                                      | 3.67 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230807-pythonperf2-x86_64-python-2ac103c346ffe9d0e4c1-3.13.0a0-2ac103c |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| xml_etree_generate   | 86.1 ms                                                      | 84.9 ms: 1.01x faster                                                       |
| json_dumps           | 10.2 ms                                                      | 10.2 ms: 1.00x faster                                                       |
| unpickle_list        | 4.77 us                                                      | 4.79 us: 1.00x slower                                                       |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                       |
| unpickle             | 14.8 us                                                      | 15.1 us: 1.02x slower                                                       |
| xml_etree_process    | 58.3 ms                                                      | 59.6 ms: 1.02x slower                                                       |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.03x slower                                                        |
| pickle_dict          | 31.7 us                                                      | 32.7 us: 1.03x slower                                                       |
| pickle_list          | 4.39 us                                                      | 4.54 us: 1.03x slower                                                       |
| json_loads           | 24.3 us                                                      | 25.7 us: 1.06x slower                                                       |
| tomli_loads          | 2.20 sec                                                     | 2.41 sec: 1.10x slower                                                      |
| unpickle_pure_python | 207 us                                                       | 236 us: 1.14x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.03x slower                                                                |

Benchmark hidden because not significant (2): pickle_pure_python, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230807-pythonperf2-x86_64-python-2ac103c346ffe9d0e4c1-3.13.0a0-2ac103c |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                      | 11.6 ms: 1.01x faster                                                       |
| python_startup_no_site | 8.70 ms                                                      | 8.63 ms: 1.01x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230807-pythonperf2-x86_64-python-2ac103c346ffe9d0e4c1-3.13.0a0-2ac103c |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230807-pythonperf2-x86_64-python-2ac103c346ffe9d0e4c1-3.13.0a0-2ac103c |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.83 ms: 1.11x faster                                                       |
| unpack_sequence          | 53.3 ns                                                      | 48.4 ns: 1.10x faster                                                       |
| crypto_pyaes             | 80.9 ms                                                      | 74.4 ms: 1.09x faster                                                       |
| raytrace                 | 302 ms                                                       | 281 ms: 1.07x faster                                                        |
| nbody                    | 94.1 ms                                                      | 89.1 ms: 1.06x faster                                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 68.7 ms: 1.05x faster                                                       |
| regex_v8                 | 25.0 ms                                                      | 24.0 ms: 1.04x faster                                                       |
| asyncio_tcp              | 381 ms                                                       | 369 ms: 1.03x faster                                                        |
| create_gc_cycles         | 1.67 ms                                                      | 1.64 ms: 1.02x faster                                                       |
| pprint_safe_repr         | 823 ms                                                       | 808 ms: 1.02x faster                                                        |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.34 ms: 1.02x faster                                                       |
| pathlib                  | 19.8 ms                                                      | 19.5 ms: 1.02x faster                                                       |
| scimark_lu               | 101 ms                                                       | 99.0 ms: 1.02x faster                                                       |
| pidigits                 | 264 ms                                                       | 260 ms: 1.02x faster                                                        |
| pprint_pformat           | 1.67 sec                                                     | 1.65 sec: 1.02x faster                                                      |
| xml_etree_generate       | 86.1 ms                                                      | 84.9 ms: 1.01x faster                                                       |
| python_startup           | 11.7 ms                                                      | 11.6 ms: 1.01x faster                                                       |
| python_startup_no_site   | 8.70 ms                                                      | 8.63 ms: 1.01x faster                                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.44 us: 1.01x faster                                                       |
| json_dumps               | 10.2 ms                                                      | 10.2 ms: 1.00x faster                                                       |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                      |
| unpickle_list            | 4.77 us                                                      | 4.79 us: 1.00x slower                                                       |
| mdp                      | 2.53 sec                                                     | 2.55 sec: 1.01x slower                                                      |
| deepcopy_memo            | 37.4 us                                                      | 37.7 us: 1.01x slower                                                       |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                       |
| mypy2                    | 368 ms                                                       | 372 ms: 1.01x slower                                                        |
| logging_format           | 7.37 us                                                      | 7.44 us: 1.01x slower                                                       |
| comprehensions           | 21.9 us                                                      | 22.1 us: 1.01x slower                                                       |
| docutils                 | 2.89 sec                                                     | 2.92 sec: 1.01x slower                                                      |
| scimark_fft              | 304 ms                                                       | 308 ms: 1.01x slower                                                        |
| logging_silent           | 95.6 ns                                                      | 97.0 ns: 1.01x slower                                                       |
| logging_simple           | 6.73 us                                                      | 6.83 us: 1.01x slower                                                       |
| json                     | 5.14 ms                                                      | 5.22 ms: 1.02x slower                                                       |
| sqlglot_transpile        | 1.80 ms                                                      | 1.83 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 717 ms: 1.02x slower                                                        |
| sqlglot_parse            | 1.40 ms                                                      | 1.43 ms: 1.02x slower                                                       |
| meteor_contest           | 128 ms                                                       | 130 ms: 1.02x slower                                                        |
| sqlglot_optimize         | 57.8 ms                                                      | 58.8 ms: 1.02x slower                                                       |
| unpickle                 | 14.8 us                                                      | 15.1 us: 1.02x slower                                                       |
| generators               | 36.7 ms                                                      | 37.4 ms: 1.02x slower                                                       |
| nqueens                  | 90.1 ms                                                      | 91.9 ms: 1.02x slower                                                       |
| deepcopy                 | 376 us                                                       | 384 us: 1.02x slower                                                        |
| xml_etree_process        | 58.3 ms                                                      | 59.6 ms: 1.02x slower                                                       |
| async_tree_io            | 1.06 sec                                                     | 1.08 sec: 1.02x slower                                                      |
| sqlite_synth             | 2.70 us                                                      | 2.76 us: 1.02x slower                                                       |
| async_tree_memoization   | 553 ms                                                       | 567 ms: 1.02x slower                                                        |
| async_tree_none          | 459 ms                                                       | 470 ms: 1.03x slower                                                        |
| async_generators         | 385 ms                                                       | 395 ms: 1.03x slower                                                        |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.03x slower                                                        |
| pickle_dict              | 31.7 us                                                      | 32.7 us: 1.03x slower                                                       |
| coroutines               | 23.0 ms                                                      | 23.7 ms: 1.03x slower                                                       |
| regex_compile            | 146 ms                                                       | 151 ms: 1.03x slower                                                        |
| typing_runtime_protocols | 151 us                                                       | 156 us: 1.03x slower                                                        |
| pickle_list              | 4.39 us                                                      | 4.54 us: 1.03x slower                                                       |
| spectral_norm            | 91.6 ms                                                      | 94.8 ms: 1.04x slower                                                       |
| float                    | 78.5 ms                                                      | 81.3 ms: 1.04x slower                                                       |
| mako                     | 9.94 ms                                                      | 10.3 ms: 1.04x slower                                                       |
| pycparser                | 1.27 sec                                                     | 1.32 sec: 1.04x slower                                                      |
| dulwich_log              | 65.3 ms                                                      | 68.2 ms: 1.04x slower                                                       |
| regex_dna                | 241 ms                                                       | 252 ms: 1.05x slower                                                        |
| regex_effbot             | 3.47 ms                                                      | 3.67 ms: 1.06x slower                                                       |
| json_loads               | 24.3 us                                                      | 25.7 us: 1.06x slower                                                       |
| tomli_loads              | 2.20 sec                                                     | 2.41 sec: 1.10x slower                                                      |
| hexiom                   | 5.96 ms                                                      | 6.53 ms: 1.10x slower                                                       |
| deltablue                | 3.29 ms                                                      | 3.67 ms: 1.12x slower                                                       |
| fannkuch                 | 350 ms                                                       | 394 ms: 1.13x slower                                                        |
| unpickle_pure_python     | 207 us                                                       | 236 us: 1.14x slower                                                        |
| pyflate                  | 447 ms                                                       | 514 ms: 1.15x slower                                                        |
| go                       | 150 ms                                                       | 174 ms: 1.16x slower                                                        |
| telco                    | 6.96 ms                                                      | 8.15 ms: 1.17x slower                                                       |
| richards_super           | 51.7 ms                                                      | 62.0 ms: 1.20x slower                                                       |
| richards                 | 45.0 ms                                                      | 55.5 ms: 1.23x slower                                                       |
| scimark_sor              | 110 ms                                                       | 144 ms: 1.31x slower                                                        |
| dask                     | 397 ms                                                       | 589 ms: 1.49x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.03x slower                                                                |

Benchmark hidden because not significant (8): bench_thread_pool, tornado_http, gc_traversal, pickle_pure_python, chaos, coverage, sqlglot_normalize, xml_etree_parse
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 99.93% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
