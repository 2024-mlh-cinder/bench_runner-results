
# Results vs. base

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 9c8ccf6
- commit date: 2023-09-05
- overall geometric mean: 1.00x faster
- HPT reliability: 94.94%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 80.1 ms                                                               | 79.1 ms: 1.01x faster                                          |
| pidigits       | 187 ms                                                                | 188 ms: 1.00x slower                                           |
| nbody          | 90.0 ms                                                               | 92.3 ms: 1.03x slower                                          |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.83 ms                                                               | 3.74 ms: 1.02x faster                                          |
| regex_dna      | 223 ms                                                                | 220 ms: 1.01x faster                                           |
| regex_compile  | 135 ms                                                                | 135 ms: 1.00x faster                                           |
| regex_v8       | 24.4 ms                                                               | 24.6 ms: 1.01x slower                                          |
| Geometric mean | (ref)                                                                 | 1.01x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle             | 14.7 us                                                               | 14.5 us: 1.01x faster                                          |
| pickle_pure_python   | 298 us                                                                | 294 us: 1.01x faster                                           |
| unpickle_pure_python | 213 us                                                                | 210 us: 1.01x faster                                           |
| pickle               | 10.6 us                                                               | 10.5 us: 1.01x faster                                          |
| xml_etree_iterparse  | 102 ms                                                                | 101 ms: 1.01x faster                                           |
| unpickle_list        | 5.11 us                                                               | 5.06 us: 1.01x faster                                          |
| xml_etree_generate   | 82.1 ms                                                               | 81.3 ms: 1.01x faster                                          |
| xml_etree_process    | 56.8 ms                                                               | 56.4 ms: 1.01x faster                                          |
| pickle_dict          | 31.3 us                                                               | 31.5 us: 1.00x slower                                          |
| json_loads           | 25.1 us                                                               | 25.4 us: 1.01x slower                                          |
| pickle_list          | 4.61 us                                                               | 4.66 us: 1.01x slower                                          |
| tomli_loads          | 2.03 sec                                                              | 2.12 sec: 1.04x slower                                         |
| Geometric mean       | (ref)                                                                 | 1.00x faster                                                   |

Benchmark hidden because not significant (2): xml_etree_parse, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.50 ms                                                               | 9.48 ms: 1.00x faster                                          |
| python_startup_no_site | 6.97 ms                                                               | 6.97 ms: 1.00x faster                                          |
| Geometric mean         | (ref)                                                                 | 1.00x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.0 ms                                                               | 10.7 ms: 1.03x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|--------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------:|
| unpack_sequence          | 53.3 ns                                                               | 45.0 ns: 1.19x faster                                          |
| mdp                      | 2.72 sec                                                              | 2.57 sec: 1.06x faster                                         |
| typing_runtime_protocols | 146 us                                                                | 142 us: 1.03x faster                                           |
| mako                     | 11.0 ms                                                               | 10.7 ms: 1.03x faster                                          |
| pprint_safe_repr         | 742 ms                                                                | 724 ms: 1.02x faster                                           |
| regex_effbot             | 3.83 ms                                                               | 3.74 ms: 1.02x faster                                          |
| logging_format           | 6.63 us                                                               | 6.51 us: 1.02x faster                                          |
| fannkuch                 | 382 ms                                                                | 375 ms: 1.02x faster                                           |
| scimark_lu               | 111 ms                                                                | 109 ms: 1.02x faster                                           |
| coroutines               | 22.4 ms                                                               | 22.1 ms: 1.02x faster                                          |
| richards_super           | 54.6 ms                                                               | 53.7 ms: 1.02x faster                                          |
| pprint_pformat           | 1.50 sec                                                              | 1.48 sec: 1.02x faster                                         |
| go                       | 141 ms                                                                | 139 ms: 1.02x faster                                           |
| sqlglot_parse            | 1.27 ms                                                               | 1.25 ms: 1.02x faster                                          |
| unpickle                 | 14.7 us                                                               | 14.5 us: 1.01x faster                                          |
| deltablue                | 3.30 ms                                                               | 3.26 ms: 1.01x faster                                          |
| hexiom                   | 6.05 ms                                                               | 5.97 ms: 1.01x faster                                          |
| regex_dna                | 223 ms                                                                | 220 ms: 1.01x faster                                           |
| pickle_pure_python       | 298 us                                                                | 294 us: 1.01x faster                                           |
| unpickle_pure_python     | 213 us                                                                | 210 us: 1.01x faster                                           |
| crypto_pyaes             | 69.4 ms                                                               | 68.5 ms: 1.01x faster                                          |
| float                    | 80.1 ms                                                               | 79.1 ms: 1.01x faster                                          |
| pickle                   | 10.6 us                                                               | 10.5 us: 1.01x faster                                          |
| pycparser                | 1.21 sec                                                              | 1.20 sec: 1.01x faster                                         |
| xml_etree_iterparse      | 102 ms                                                                | 101 ms: 1.01x faster                                           |
| unpickle_list            | 5.11 us                                                               | 5.06 us: 1.01x faster                                          |
| logging_simple           | 5.98 us                                                               | 5.92 us: 1.01x faster                                          |
| chaos                    | 59.2 ms                                                               | 58.7 ms: 1.01x faster                                          |
| xml_etree_generate       | 82.1 ms                                                               | 81.3 ms: 1.01x faster                                          |
| xml_etree_process        | 56.8 ms                                                               | 56.4 ms: 1.01x faster                                          |
| telco                    | 8.03 ms                                                               | 7.96 ms: 1.01x faster                                          |
| sqlglot_transpile        | 1.58 ms                                                               | 1.56 ms: 1.01x faster                                          |
| sqlglot_optimize         | 52.6 ms                                                               | 52.2 ms: 1.01x faster                                          |
| sqlglot_normalize        | 104 ms                                                                | 103 ms: 1.01x faster                                           |
| bench_thread_pool        | 814 us                                                                | 811 us: 1.00x faster                                           |
| regex_compile            | 135 ms                                                                | 135 ms: 1.00x faster                                           |
| nqueens                  | 80.0 ms                                                               | 79.7 ms: 1.00x faster                                          |
| create_gc_cycles         | 1.50 ms                                                               | 1.50 ms: 1.00x faster                                          |
| python_startup           | 9.50 ms                                                               | 9.48 ms: 1.00x faster                                          |
| python_startup_no_site   | 6.97 ms                                                               | 6.97 ms: 1.00x faster                                          |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.80 sec: 1.00x slower                                         |
| generators               | 28.9 ms                                                               | 29.0 ms: 1.00x slower                                          |
| pickle_dict              | 31.3 us                                                               | 31.5 us: 1.00x slower                                          |
| pidigits                 | 187 ms                                                                | 188 ms: 1.00x slower                                           |
| pyflate                  | 450 ms                                                                | 452 ms: 1.00x slower                                           |
| asyncio_tcp              | 486 ms                                                                | 489 ms: 1.01x slower                                           |
| raytrace                 | 271 ms                                                                | 273 ms: 1.01x slower                                           |
| dulwich_log              | 66.6 ms                                                               | 67.2 ms: 1.01x slower                                          |
| regex_v8                 | 24.4 ms                                                               | 24.6 ms: 1.01x slower                                          |
| deepcopy                 | 343 us                                                                | 346 us: 1.01x slower                                           |
| json_loads               | 25.1 us                                                               | 25.4 us: 1.01x slower                                          |
| pickle_list              | 4.61 us                                                               | 4.66 us: 1.01x slower                                          |
| scimark_fft              | 350 ms                                                                | 356 ms: 1.02x slower                                           |
| nbody                    | 90.0 ms                                                               | 92.3 ms: 1.03x slower                                          |
| pathlib                  | 18.3 ms                                                               | 18.8 ms: 1.03x slower                                          |
| tomli_loads              | 2.03 sec                                                              | 2.12 sec: 1.04x slower                                         |
| scimark_sparse_mat_mult  | 4.66 ms                                                               | 4.89 ms: 1.05x slower                                          |
| gc_traversal             | 3.83 ms                                                               | 4.08 ms: 1.06x slower                                          |
| Geometric mean           | (ref)                                                                 | 1.00x faster                                                   |

Benchmark hidden because not significant (24): richards, xml_etree_parse, scimark_sor, async_tree_cpu_io_mixed, logging_silent, dask, async_tree_memoization, mypy2, async_tree_io, spectral_norm, bench_mp_pool, json_dumps, comprehensions, async_generators, docutils, meteor_contest, deepcopy_memo, coverage, tornado_http, deepcopy_reduce, sqlite_synth, scimark_monte_carlo, async_tree_none, json


# HPT report

- Reliability score: 94.94% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
