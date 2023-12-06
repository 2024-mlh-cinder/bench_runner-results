
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                              |
| Geometric mean | (ref)                                                        | 1.01x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 264 ms                                                       | 266 ms: 1.01x slower                                                |
| float          | 78.5 ms                                                      | 84.9 ms: 1.08x slower                                               |
| nbody          | 94.1 ms                                                      | 127 ms: 1.35x slower                                                |
| Geometric mean | (ref)                                                        | 1.14x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 3.47 ms                                                      | 3.50 ms: 1.01x slower                                               |
| regex_dna      | 241 ms                                                       | 245 ms: 1.02x slower                                                |
| regex_v8       | 25.0 ms                                                      | 26.3 ms: 1.05x slower                                               |
| regex_compile  | 146 ms                                                       | 159 ms: 1.09x slower                                                |
| Geometric mean | (ref)                                                        | 1.04x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle_list        | 4.77 us                                                      | 4.57 us: 1.04x faster                                               |
| pickle_list          | 4.39 us                                                      | 4.30 us: 1.02x faster                                               |
| pickle_pure_python   | 323 us                                                       | 317 us: 1.02x faster                                                |
| xml_etree_generate   | 86.1 ms                                                      | 85.7 ms: 1.01x faster                                               |
| unpickle             | 14.8 us                                                      | 14.9 us: 1.01x slower                                               |
| pickle_dict          | 31.7 us                                                      | 32.2 us: 1.02x slower                                               |
| xml_etree_process    | 58.3 ms                                                      | 59.5 ms: 1.02x slower                                               |
| xml_etree_iterparse  | 103 ms                                                       | 106 ms: 1.03x slower                                                |
| json_dumps           | 10.2 ms                                                      | 10.7 ms: 1.04x slower                                               |
| json_loads           | 24.3 us                                                      | 25.4 us: 1.05x slower                                               |
| tomli_loads          | 2.20 sec                                                     | 2.44 sec: 1.11x slower                                              |
| unpickle_pure_python | 207 us                                                       | 232 us: 1.12x slower                                                |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                        |

Benchmark hidden because not significant (2): pickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                               |
| Geometric mean | (ref)                                                        | 1.04x slower                                                        |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.9 ms: 1.10x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.67 ms: 1.14x faster                                               |
| raytrace                 | 302 ms                                                       | 271 ms: 1.11x faster                                                |
| coverage                 | 89.6 ms                                                      | 80.6 ms: 1.11x faster                                               |
| crypto_pyaes             | 80.9 ms                                                      | 76.6 ms: 1.06x faster                                               |
| unpickle_list            | 4.77 us                                                      | 4.57 us: 1.04x faster                                               |
| async_tree_none          | 459 ms                                                       | 440 ms: 1.04x faster                                                |
| create_gc_cycles         | 1.67 ms                                                      | 1.61 ms: 1.04x faster                                               |
| asyncio_tcp              | 381 ms                                                       | 371 ms: 1.03x faster                                                |
| deepcopy_reduce          | 3.46 us                                                      | 3.37 us: 1.03x faster                                               |
| pickle_list              | 4.39 us                                                      | 4.30 us: 1.02x faster                                               |
| pickle_pure_python       | 323 us                                                       | 317 us: 1.02x faster                                                |
| xml_etree_generate       | 86.1 ms                                                      | 85.7 ms: 1.01x faster                                               |
| pprint_safe_repr         | 823 ms                                                       | 819 ms: 1.00x faster                                                |
| pprint_pformat           | 1.67 sec                                                     | 1.67 sec: 1.00x faster                                              |
| sqlite_synth             | 2.70 us                                                      | 2.71 us: 1.00x slower                                               |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                              |
| pidigits                 | 264 ms                                                       | 266 ms: 1.01x slower                                                |
| unpickle                 | 14.8 us                                                      | 14.9 us: 1.01x slower                                               |
| regex_effbot             | 3.47 ms                                                      | 3.50 ms: 1.01x slower                                               |
| spectral_norm            | 91.6 ms                                                      | 92.5 ms: 1.01x slower                                               |
| pathlib                  | 19.8 ms                                                      | 20.0 ms: 1.01x slower                                               |
| generators               | 36.7 ms                                                      | 37.2 ms: 1.01x slower                                               |
| scimark_monte_carlo      | 72.4 ms                                                      | 73.4 ms: 1.01x slower                                               |
| pickle_dict              | 31.7 us                                                      | 32.2 us: 1.02x slower                                               |
| regex_dna                | 241 ms                                                       | 245 ms: 1.02x slower                                                |
| logging_simple           | 6.73 us                                                      | 6.87 us: 1.02x slower                                               |
| xml_etree_process        | 58.3 ms                                                      | 59.5 ms: 1.02x slower                                               |
| coroutines               | 23.0 ms                                                      | 23.5 ms: 1.02x slower                                               |
| docutils                 | 2.89 sec                                                     | 2.95 sec: 1.02x slower                                              |
| pycparser                | 1.27 sec                                                     | 1.30 sec: 1.02x slower                                              |
| logging_format           | 7.37 us                                                      | 7.54 us: 1.02x slower                                               |
| deepcopy                 | 376 us                                                       | 386 us: 1.03x slower                                                |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                              |
| sqlglot_parse            | 1.40 ms                                                      | 1.44 ms: 1.03x slower                                               |
| sqlglot_normalize        | 117 ms                                                       | 120 ms: 1.03x slower                                                |
| xml_etree_iterparse      | 103 ms                                                       | 106 ms: 1.03x slower                                                |
| sqlglot_transpile        | 1.80 ms                                                      | 1.86 ms: 1.03x slower                                               |
| logging_silent           | 95.6 ns                                                      | 99.4 ns: 1.04x slower                                               |
| json_dumps               | 10.2 ms                                                      | 10.7 ms: 1.04x slower                                               |
| json_loads               | 24.3 us                                                      | 25.4 us: 1.05x slower                                               |
| sqlglot_optimize         | 57.8 ms                                                      | 60.6 ms: 1.05x slower                                               |
| mypy2                    | 368 ms                                                       | 387 ms: 1.05x slower                                                |
| regex_v8                 | 25.0 ms                                                      | 26.3 ms: 1.05x slower                                               |
| typing_runtime_protocols | 151 us                                                       | 160 us: 1.06x slower                                                |
| mdp                      | 2.53 sec                                                     | 2.71 sec: 1.07x slower                                              |
| deepcopy_memo            | 37.4 us                                                      | 40.0 us: 1.07x slower                                               |
| dulwich_log              | 65.3 ms                                                      | 69.9 ms: 1.07x slower                                               |
| scimark_lu               | 101 ms                                                       | 108 ms: 1.08x slower                                                |
| async_generators         | 385 ms                                                       | 415 ms: 1.08x slower                                                |
| unpack_sequence          | 53.3 ns                                                      | 57.6 ns: 1.08x slower                                               |
| float                    | 78.5 ms                                                      | 84.9 ms: 1.08x slower                                               |
| python_startup           | 11.7 ms                                                      | 12.7 ms: 1.08x slower                                               |
| meteor_contest           | 128 ms                                                       | 139 ms: 1.08x slower                                                |
| regex_compile            | 146 ms                                                       | 159 ms: 1.09x slower                                                |
| mako                     | 9.94 ms                                                      | 10.9 ms: 1.10x slower                                               |
| tomli_loads              | 2.20 sec                                                     | 2.44 sec: 1.11x slower                                              |
| gc_traversal             | 3.54 ms                                                      | 3.95 ms: 1.11x slower                                               |
| unpickle_pure_python     | 207 us                                                       | 232 us: 1.12x slower                                                |
| pyflate                  | 447 ms                                                       | 509 ms: 1.14x slower                                                |
| deltablue                | 3.29 ms                                                      | 3.77 ms: 1.15x slower                                               |
| chaos                    | 62.9 ms                                                      | 72.2 ms: 1.15x slower                                               |
| richards_super           | 51.7 ms                                                      | 61.2 ms: 1.18x slower                                               |
| telco                    | 6.96 ms                                                      | 8.26 ms: 1.19x slower                                               |
| go                       | 150 ms                                                       | 179 ms: 1.19x slower                                                |
| comprehensions           | 21.9 us                                                      | 26.3 us: 1.20x slower                                               |
| richards                 | 45.0 ms                                                      | 55.1 ms: 1.22x slower                                               |
| nqueens                  | 90.1 ms                                                      | 111 ms: 1.23x slower                                                |
| fannkuch                 | 350 ms                                                       | 437 ms: 1.25x slower                                                |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 5.63 ms: 1.27x slower                                               |
| hexiom                   | 5.96 ms                                                      | 7.64 ms: 1.28x slower                                               |
| scimark_fft              | 304 ms                                                       | 398 ms: 1.31x slower                                                |
| scimark_sor              | 110 ms                                                       | 148 ms: 1.35x slower                                                |
| nbody                    | 94.1 ms                                                      | 127 ms: 1.35x slower                                                |
| dask                     | 397 ms                                                       | 595 ms: 1.50x slower                                                |
| Geometric mean           | (ref)                                                        | 1.06x slower                                                        |

Benchmark hidden because not significant (8): bench_thread_pool, python_startup_no_site, async_tree_cpu_io_mixed, json, pickle, async_tree_memoization, xml_etree_parse, tornado_http
Ignored benchmarks (1) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
