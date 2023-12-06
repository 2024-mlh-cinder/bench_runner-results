
# Results vs. base

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.01x slower
- HPT reliability: 99.59%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.91 sec                                                                    | 2.93 sec: 1.01x slower                                                     |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 80.5 ms                                                                     | 82.0 ms: 1.02x slower                                                      |
| nbody          | 85.3 ms                                                                     | 92.0 ms: 1.08x slower                                                      |
| Geometric mean | (ref)                                                                       | 1.03x slower                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.75 ms                                                                     | 3.58 ms: 1.05x faster                                                      |
| regex_v8       | 25.8 ms                                                                     | 25.2 ms: 1.03x faster                                                      |
| regex_dna      | 247 ms                                                                      | 244 ms: 1.01x faster                                                       |
| regex_compile  | 148 ms                                                                      | 154 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_loads           | 25.2 us                                                                     | 24.6 us: 1.02x faster                                                      |
| xml_etree_parse      | 149 ms                                                                      | 147 ms: 1.01x faster                                                       |
| pickle               | 10.1 us                                                                     | 10.2 us: 1.01x slower                                                      |
| unpickle_list        | 4.73 us                                                                     | 4.77 us: 1.01x slower                                                      |
| unpickle             | 14.3 us                                                                     | 14.4 us: 1.01x slower                                                      |
| pickle_dict          | 32.4 us                                                                     | 32.7 us: 1.01x slower                                                      |
| xml_etree_generate   | 83.8 ms                                                                     | 86.0 ms: 1.03x slower                                                      |
| pickle_list          | 4.36 us                                                                     | 4.49 us: 1.03x slower                                                      |
| xml_etree_process    | 57.8 ms                                                                     | 59.5 ms: 1.03x slower                                                      |
| tomli_loads          | 2.21 sec                                                                    | 2.29 sec: 1.03x slower                                                     |
| unpickle_pure_python | 228 us                                                                      | 241 us: 1.06x slower                                                       |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (3): json_dumps, pickle_pure_python, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 11.9 ms                                                                     | 11.9 ms: 1.00x faster                                                      |
| Geometric mean | (ref)                                                                       | 1.00x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 10.2 ms                                                                     | 10.5 ms: 1.03x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| gc_traversal             | 3.98 ms                                                                     | 3.68 ms: 1.08x faster                                                      |
| create_gc_cycles         | 1.68 ms                                                                     | 1.57 ms: 1.07x faster                                                      |
| regex_effbot             | 3.75 ms                                                                     | 3.58 ms: 1.05x faster                                                      |
| pyflate                  | 515 ms                                                                      | 495 ms: 1.04x faster                                                       |
| deepcopy_reduce          | 3.50 us                                                                     | 3.36 us: 1.04x faster                                                      |
| richards                 | 55.4 ms                                                                     | 53.4 ms: 1.04x faster                                                      |
| json                     | 5.23 ms                                                                     | 5.07 ms: 1.03x faster                                                      |
| regex_v8                 | 25.8 ms                                                                     | 25.2 ms: 1.03x faster                                                      |
| logging_format           | 7.54 us                                                                     | 7.34 us: 1.03x faster                                                      |
| coroutines               | 23.1 ms                                                                     | 22.6 ms: 1.03x faster                                                      |
| logging_simple           | 6.91 us                                                                     | 6.73 us: 1.03x faster                                                      |
| json_loads               | 25.2 us                                                                     | 24.6 us: 1.02x faster                                                      |
| pprint_safe_repr         | 818 ms                                                                      | 804 ms: 1.02x faster                                                       |
| go                       | 177 ms                                                                      | 175 ms: 1.02x faster                                                       |
| deepcopy                 | 390 us                                                                      | 384 us: 1.02x faster                                                       |
| pprint_pformat           | 1.67 sec                                                                    | 1.64 sec: 1.02x faster                                                     |
| pycparser                | 1.36 sec                                                                    | 1.34 sec: 1.02x faster                                                     |
| richards_super           | 61.7 ms                                                                     | 60.9 ms: 1.01x faster                                                      |
| raytrace                 | 279 ms                                                                      | 276 ms: 1.01x faster                                                       |
| xml_etree_parse          | 149 ms                                                                      | 147 ms: 1.01x faster                                                       |
| scimark_sor              | 149 ms                                                                      | 148 ms: 1.01x faster                                                       |
| regex_dna                | 247 ms                                                                      | 244 ms: 1.01x faster                                                       |
| logging_silent           | 99.1 ns                                                                     | 98.1 ns: 1.01x faster                                                      |
| scimark_monte_carlo      | 68.6 ms                                                                     | 68.3 ms: 1.01x faster                                                      |
| python_startup           | 11.9 ms                                                                     | 11.9 ms: 1.00x faster                                                      |
| asyncio_tcp              | 372 ms                                                                      | 374 ms: 1.00x slower                                                       |
| crypto_pyaes             | 73.6 ms                                                                     | 74.0 ms: 1.00x slower                                                      |
| docutils                 | 2.91 sec                                                                    | 2.93 sec: 1.01x slower                                                     |
| pickle                   | 10.1 us                                                                     | 10.2 us: 1.01x slower                                                      |
| unpickle_list            | 4.73 us                                                                     | 4.77 us: 1.01x slower                                                      |
| dulwich_log              | 69.3 ms                                                                     | 69.9 ms: 1.01x slower                                                      |
| deltablue                | 3.71 ms                                                                     | 3.75 ms: 1.01x slower                                                      |
| unpickle                 | 14.3 us                                                                     | 14.4 us: 1.01x slower                                                      |
| pickle_dict              | 32.4 us                                                                     | 32.7 us: 1.01x slower                                                      |
| deepcopy_memo            | 38.2 us                                                                     | 38.7 us: 1.01x slower                                                      |
| pathlib                  | 19.7 ms                                                                     | 20.0 ms: 1.01x slower                                                      |
| telco                    | 8.05 ms                                                                     | 8.19 ms: 1.02x slower                                                      |
| float                    | 80.5 ms                                                                     | 82.0 ms: 1.02x slower                                                      |
| mypy2                    | 372 ms                                                                      | 380 ms: 1.02x slower                                                       |
| typing_runtime_protocols | 150 us                                                                      | 153 us: 1.02x slower                                                       |
| sqlglot_optimize         | 59.1 ms                                                                     | 60.6 ms: 1.02x slower                                                      |
| sqlglot_parse            | 1.42 ms                                                                     | 1.46 ms: 1.03x slower                                                      |
| xml_etree_generate       | 83.8 ms                                                                     | 86.0 ms: 1.03x slower                                                      |
| mako                     | 10.2 ms                                                                     | 10.5 ms: 1.03x slower                                                      |
| sqlglot_normalize        | 116 ms                                                                      | 120 ms: 1.03x slower                                                       |
| pickle_list              | 4.36 us                                                                     | 4.49 us: 1.03x slower                                                      |
| xml_etree_process        | 57.8 ms                                                                     | 59.5 ms: 1.03x slower                                                      |
| unpack_sequence          | 49.1 ns                                                                     | 50.6 ns: 1.03x slower                                                      |
| scimark_lu               | 101 ms                                                                      | 104 ms: 1.03x slower                                                       |
| sqlglot_transpile        | 1.81 ms                                                                     | 1.87 ms: 1.03x slower                                                      |
| tomli_loads              | 2.21 sec                                                                    | 2.29 sec: 1.03x slower                                                     |
| bench_thread_pool        | 960 us                                                                      | 998 us: 1.04x slower                                                       |
| async_generators         | 399 ms                                                                      | 416 ms: 1.04x slower                                                       |
| regex_compile            | 148 ms                                                                      | 154 ms: 1.04x slower                                                       |
| generators               | 35.0 ms                                                                     | 36.6 ms: 1.05x slower                                                      |
| mdp                      | 2.50 sec                                                                    | 2.62 sec: 1.05x slower                                                     |
| spectral_norm            | 90.1 ms                                                                     | 94.8 ms: 1.05x slower                                                      |
| chaos                    | 62.1 ms                                                                     | 65.3 ms: 1.05x slower                                                      |
| fannkuch                 | 390 ms                                                                      | 410 ms: 1.05x slower                                                       |
| unpickle_pure_python     | 228 us                                                                      | 241 us: 1.06x slower                                                       |
| meteor_contest           | 128 ms                                                                      | 137 ms: 1.07x slower                                                       |
| nbody                    | 85.3 ms                                                                     | 92.0 ms: 1.08x slower                                                      |
| hexiom                   | 6.43 ms                                                                     | 7.03 ms: 1.09x slower                                                      |
| scimark_fft              | 299 ms                                                                      | 329 ms: 1.10x slower                                                       |
| comprehensions           | 22.4 us                                                                     | 24.7 us: 1.10x slower                                                      |
| nqueens                  | 88.8 ms                                                                     | 98.5 ms: 1.11x slower                                                      |
| scimark_sparse_mat_mult  | 4.13 ms                                                                     | 5.15 ms: 1.25x slower                                                      |
| Geometric mean           | (ref)                                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (15): bench_mp_pool, sqlite_synth, coverage, json_dumps, asyncio_tcp_ssl, pidigits, python_startup_no_site, dask, async_tree_io, pickle_pure_python, async_tree_cpu_io_mixed, xml_etree_iterparse, async_tree_memoization, tornado_http, async_tree_none


# HPT report

- Reliability score: 99.59% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
