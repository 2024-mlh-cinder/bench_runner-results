
# Results vs. base

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 0ad7112
- commit date: 2023-08-12
- overall geometric mean: 1.00x slower
- HPT reliability: 85.67%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.63 sec: 1.00x slower                                         |
| Geometric mean | (ref)                                                                 | 1.00x slower                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 78.7 ms                                                               | 80.2 ms: 1.02x slower                                          |
| pidigits       | 189 ms                                                                | 196 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                   |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.60 ms                                                               | 3.57 ms: 1.01x faster                                          |
| regex_compile  | 136 ms                                                                | 135 ms: 1.01x faster                                           |
| regex_v8       | 24.9 ms                                                               | 25.1 ms: 1.01x slower                                          |
| regex_dna      | 214 ms                                                                | 227 ms: 1.06x slower                                           |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle_list        | 5.01 us                                                               | 4.85 us: 1.03x faster                                          |
| json_dumps           | 9.96 ms                                                               | 9.78 ms: 1.02x faster                                          |
| xml_etree_process    | 57.5 ms                                                               | 56.7 ms: 1.01x faster                                          |
| xml_etree_parse      | 154 ms                                                                | 152 ms: 1.01x faster                                           |
| unpickle_pure_python | 214 us                                                                | 213 us: 1.01x faster                                           |
| pickle_dict          | 31.9 us                                                               | 32.2 us: 1.01x slower                                          |
| pickle_pure_python   | 299 us                                                                | 303 us: 1.01x slower                                           |
| pickle_list          | 4.64 us                                                               | 4.75 us: 1.02x slower                                          |
| pickle               | 10.6 us                                                               | 10.9 us: 1.02x slower                                          |
| unpickle             | 14.6 us                                                               | 15.2 us: 1.04x slower                                          |
| Geometric mean       | (ref)                                                                 | 1.00x slower                                                   |

Benchmark hidden because not significant (4): tomli_loads, json_loads, xml_etree_generate, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.52 ms                                                               | 9.56 ms: 1.00x slower                                          |
| python_startup_no_site | 6.97 ms                                                               | 7.00 ms: 1.00x slower                                          |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.8 ms                                                               | 10.9 ms: 1.01x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20230831-linux-x86_64-python-c1e2f3b2f70b8a72ea7e-3.13.0a0-c1e2f3b | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|--------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mdp                      | 2.73 sec                                                              | 2.57 sec: 1.06x faster                                         |
| unpack_sequence          | 51.5 ns                                                               | 48.7 ns: 1.06x faster                                          |
| fannkuch                 | 396 ms                                                                | 382 ms: 1.04x faster                                           |
| unpickle_list            | 5.01 us                                                               | 4.85 us: 1.03x faster                                          |
| sqlglot_normalize        | 106 ms                                                                | 103 ms: 1.03x faster                                           |
| pprint_safe_repr         | 741 ms                                                                | 721 ms: 1.03x faster                                           |
| pprint_pformat           | 1.51 sec                                                              | 1.47 sec: 1.03x faster                                         |
| sqlglot_optimize         | 53.3 ms                                                               | 52.0 ms: 1.03x faster                                          |
| scimark_sparse_mat_mult  | 4.74 ms                                                               | 4.62 ms: 1.03x faster                                          |
| scimark_sor              | 121 ms                                                                | 119 ms: 1.02x faster                                           |
| hexiom                   | 6.01 ms                                                               | 5.90 ms: 1.02x faster                                          |
| json_dumps               | 9.96 ms                                                               | 9.78 ms: 1.02x faster                                          |
| logging_silent           | 103 ns                                                                | 102 ns: 1.02x faster                                           |
| sqlglot_parse            | 1.28 ms                                                               | 1.26 ms: 1.02x faster                                          |
| chaos                    | 60.3 ms                                                               | 59.5 ms: 1.01x faster                                          |
| xml_etree_process        | 57.5 ms                                                               | 56.7 ms: 1.01x faster                                          |
| richards_super           | 53.9 ms                                                               | 53.3 ms: 1.01x faster                                          |
| scimark_lu               | 112 ms                                                                | 110 ms: 1.01x faster                                           |
| telco                    | 8.01 ms                                                               | 7.91 ms: 1.01x faster                                          |
| crypto_pyaes             | 68.6 ms                                                               | 67.8 ms: 1.01x faster                                          |
| sqlglot_transpile        | 1.58 ms                                                               | 1.57 ms: 1.01x faster                                          |
| nqueens                  | 80.4 ms                                                               | 79.6 ms: 1.01x faster                                          |
| asyncio_tcp              | 490 ms                                                                | 485 ms: 1.01x faster                                           |
| xml_etree_parse          | 154 ms                                                                | 152 ms: 1.01x faster                                           |
| deepcopy_reduce          | 3.17 us                                                               | 3.14 us: 1.01x faster                                          |
| deepcopy_memo            | 37.7 us                                                               | 37.4 us: 1.01x faster                                          |
| regex_effbot             | 3.60 ms                                                               | 3.57 ms: 1.01x faster                                          |
| regex_compile            | 136 ms                                                                | 135 ms: 1.01x faster                                           |
| unpickle_pure_python     | 214 us                                                                | 213 us: 1.01x faster                                           |
| deepcopy                 | 350 us                                                                | 348 us: 1.01x faster                                           |
| async_tree_io            | 1.19 sec                                                              | 1.19 sec: 1.00x faster                                         |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.79 sec: 1.00x faster                                         |
| docutils                 | 2.62 sec                                                              | 2.63 sec: 1.00x slower                                         |
| python_startup           | 9.52 ms                                                               | 9.56 ms: 1.00x slower                                          |
| python_startup_no_site   | 6.97 ms                                                               | 7.00 ms: 1.00x slower                                          |
| pyflate                  | 444 ms                                                                | 446 ms: 1.00x slower                                           |
| go                       | 139 ms                                                                | 140 ms: 1.01x slower                                           |
| spectral_norm            | 103 ms                                                                | 104 ms: 1.01x slower                                           |
| scimark_fft              | 352 ms                                                                | 355 ms: 1.01x slower                                           |
| regex_v8                 | 24.9 ms                                                               | 25.1 ms: 1.01x slower                                          |
| pickle_dict              | 31.9 us                                                               | 32.2 us: 1.01x slower                                          |
| generators               | 28.8 ms                                                               | 29.0 ms: 1.01x slower                                          |
| pathlib                  | 18.6 ms                                                               | 18.7 ms: 1.01x slower                                          |
| mako                     | 10.8 ms                                                               | 10.9 ms: 1.01x slower                                          |
| scimark_monte_carlo      | 66.2 ms                                                               | 66.9 ms: 1.01x slower                                          |
| pickle_pure_python       | 299 us                                                                | 303 us: 1.01x slower                                           |
| sqlite_synth             | 2.72 us                                                               | 2.75 us: 1.01x slower                                          |
| logging_simple           | 5.93 us                                                               | 5.99 us: 1.01x slower                                          |
| typing_runtime_protocols | 140 us                                                                | 142 us: 1.01x slower                                           |
| dulwich_log              | 66.0 ms                                                               | 67.0 ms: 1.02x slower                                          |
| float                    | 78.7 ms                                                               | 80.2 ms: 1.02x slower                                          |
| create_gc_cycles         | 1.47 ms                                                               | 1.51 ms: 1.02x slower                                          |
| pickle_list              | 4.64 us                                                               | 4.75 us: 1.02x slower                                          |
| pickle                   | 10.6 us                                                               | 10.9 us: 1.02x slower                                          |
| pycparser                | 1.17 sec                                                              | 1.20 sec: 1.03x slower                                         |
| pidigits                 | 189 ms                                                                | 196 ms: 1.04x slower                                           |
| unpickle                 | 14.6 us                                                               | 15.2 us: 1.04x slower                                          |
| coroutines               | 22.1 ms                                                               | 23.2 ms: 1.05x slower                                          |
| regex_dna                | 214 ms                                                                | 227 ms: 1.06x slower                                           |
| gc_traversal             | 3.66 ms                                                               | 4.31 ms: 1.18x slower                                          |
| Geometric mean           | (ref)                                                                 | 1.00x slower                                                   |

Benchmark hidden because not significant (22): async_tree_none, tomli_loads, logging_format, json_loads, async_tree_memoization, richards, mypy2, coverage, async_tree_cpu_io_mixed, tornado_http, meteor_contest, bench_mp_pool, comprehensions, xml_etree_generate, xml_etree_iterparse, bench_thread_pool, raytrace, dask, json, async_generators, nbody, deltablue


# HPT report

- Reliability score: 85.67% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
