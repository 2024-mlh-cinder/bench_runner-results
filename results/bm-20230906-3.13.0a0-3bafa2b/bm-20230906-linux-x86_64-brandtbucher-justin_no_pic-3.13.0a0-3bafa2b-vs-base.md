
# Results vs. base

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.67 sec: 1.02x slower                                               |
| tornado_http   | 95.2 ms                                                               | 96.6 ms: 1.01x slower                                                |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 187 ms: 1.00x slower                                                 |
| float          | 78.2 ms                                                               | 81.7 ms: 1.05x slower                                                |
| nbody          | 88.7 ms                                                               | 95.5 ms: 1.08x slower                                                |
| Geometric mean | (ref)                                                                 | 1.04x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_dna      | 216 ms                                                                | 211 ms: 1.02x faster                                                 |
| regex_effbot   | 3.58 ms                                                               | 3.54 ms: 1.01x faster                                                |
| regex_v8       | 24.6 ms                                                               | 25.0 ms: 1.02x slower                                                |
| regex_compile  | 134 ms                                                                | 141 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_list          | 4.62 us                                                               | 4.46 us: 1.04x faster                                                |
| pickle_dict          | 32.6 us                                                               | 31.8 us: 1.03x faster                                                |
| unpickle_list        | 4.89 us                                                               | 4.82 us: 1.02x faster                                                |
| pickle_pure_python   | 295 us                                                                | 297 us: 1.01x slower                                                 |
| json_loads           | 24.9 us                                                               | 25.2 us: 1.01x slower                                                |
| pickle               | 10.7 us                                                               | 10.8 us: 1.01x slower                                                |
| json_dumps           | 9.72 ms                                                               | 9.85 ms: 1.01x slower                                                |
| xml_etree_generate   | 81.5 ms                                                               | 83.5 ms: 1.02x slower                                                |
| xml_etree_process    | 56.2 ms                                                               | 57.8 ms: 1.03x slower                                                |
| xml_etree_iterparse  | 102 ms                                                                | 105 ms: 1.03x slower                                                 |
| tomli_loads          | 2.02 sec                                                              | 2.15 sec: 1.06x slower                                               |
| unpickle_pure_python | 212 us                                                                | 228 us: 1.08x slower                                                 |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                         |

Benchmark hidden because not significant (2): unpickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 9.51 ms                                                               | 9.52 ms: 1.00x slower                                                |
| python_startup_no_site | 6.98 ms                                                               | 7.00 ms: 1.00x slower                                                |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.5 ms                                                               | 11.2 ms: 1.06x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| gc_traversal             | 4.33 ms                                                               | 3.94 ms: 1.10x faster                                                |
| pickle_list              | 4.62 us                                                               | 4.46 us: 1.04x faster                                                |
| json                     | 4.91 ms                                                               | 4.75 ms: 1.03x faster                                                |
| pickle_dict              | 32.6 us                                                               | 31.8 us: 1.03x faster                                                |
| regex_dna                | 216 ms                                                                | 211 ms: 1.02x faster                                                 |
| coroutines               | 22.6 ms                                                               | 22.1 ms: 1.02x faster                                                |
| unpickle_list            | 4.89 us                                                               | 4.82 us: 1.02x faster                                                |
| coverage                 | 86.6 ms                                                               | 85.5 ms: 1.01x faster                                                |
| regex_effbot             | 3.58 ms                                                               | 3.54 ms: 1.01x faster                                                |
| deepcopy_reduce          | 3.10 us                                                               | 3.07 us: 1.01x faster                                                |
| create_gc_cycles         | 1.49 ms                                                               | 1.48 ms: 1.01x faster                                                |
| sqlite_synth             | 2.76 us                                                               | 2.74 us: 1.01x faster                                                |
| python_startup           | 9.51 ms                                                               | 9.52 ms: 1.00x slower                                                |
| pidigits                 | 187 ms                                                                | 187 ms: 1.00x slower                                                 |
| python_startup_no_site   | 6.98 ms                                                               | 7.00 ms: 1.00x slower                                                |
| async_tree_io            | 1.19 sec                                                              | 1.20 sec: 1.01x slower                                               |
| pickle_pure_python       | 295 us                                                                | 297 us: 1.01x slower                                                 |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.80 sec: 1.01x slower                                               |
| json_loads               | 24.9 us                                                               | 25.2 us: 1.01x slower                                                |
| pickle                   | 10.7 us                                                               | 10.8 us: 1.01x slower                                                |
| logging_simple           | 5.89 us                                                               | 5.96 us: 1.01x slower                                                |
| asyncio_tcp              | 488 ms                                                                | 493 ms: 1.01x slower                                                 |
| richards_super           | 53.8 ms                                                               | 54.5 ms: 1.01x slower                                                |
| pathlib                  | 18.6 ms                                                               | 18.8 ms: 1.01x slower                                                |
| logging_format           | 6.52 us                                                               | 6.60 us: 1.01x slower                                                |
| json_dumps               | 9.72 ms                                                               | 9.85 ms: 1.01x slower                                                |
| pycparser                | 1.16 sec                                                              | 1.17 sec: 1.01x slower                                               |
| raytrace                 | 273 ms                                                                | 277 ms: 1.01x slower                                                 |
| tornado_http             | 95.2 ms                                                               | 96.6 ms: 1.01x slower                                                |
| regex_v8                 | 24.6 ms                                                               | 25.0 ms: 1.02x slower                                                |
| pprint_safe_repr         | 724 ms                                                                | 738 ms: 1.02x slower                                                 |
| scimark_sparse_mat_mult  | 4.63 ms                                                               | 4.71 ms: 1.02x slower                                                |
| dask                     | 519 ms                                                                | 530 ms: 1.02x slower                                                 |
| docutils                 | 2.62 sec                                                              | 2.67 sec: 1.02x slower                                               |
| deepcopy                 | 345 us                                                                | 353 us: 1.02x slower                                                 |
| generators               | 28.9 ms                                                               | 29.5 ms: 1.02x slower                                                |
| logging_silent           | 102 ns                                                                | 104 ns: 1.02x slower                                                 |
| dulwich_log              | 66.4 ms                                                               | 67.9 ms: 1.02x slower                                                |
| xml_etree_generate       | 81.5 ms                                                               | 83.5 ms: 1.02x slower                                                |
| xml_etree_process        | 56.2 ms                                                               | 57.8 ms: 1.03x slower                                                |
| sqlglot_parse            | 1.26 ms                                                               | 1.29 ms: 1.03x slower                                                |
| sqlglot_optimize         | 52.3 ms                                                               | 53.9 ms: 1.03x slower                                                |
| sqlglot_normalize        | 103 ms                                                                | 106 ms: 1.03x slower                                                 |
| scimark_monte_carlo      | 65.6 ms                                                               | 67.6 ms: 1.03x slower                                                |
| xml_etree_iterparse      | 102 ms                                                                | 105 ms: 1.03x slower                                                 |
| bench_thread_pool        | 813 us                                                                | 839 us: 1.03x slower                                                 |
| pprint_pformat           | 1.47 sec                                                              | 1.51 sec: 1.03x slower                                               |
| telco                    | 7.98 ms                                                               | 8.24 ms: 1.03x slower                                                |
| scimark_fft              | 349 ms                                                                | 361 ms: 1.03x slower                                                 |
| sqlglot_transpile        | 1.56 ms                                                               | 1.62 ms: 1.04x slower                                                |
| mypy2                    | 337 ms                                                                | 349 ms: 1.04x slower                                                 |
| deltablue                | 3.28 ms                                                               | 3.40 ms: 1.04x slower                                                |
| scimark_sor              | 118 ms                                                                | 122 ms: 1.04x slower                                                 |
| scimark_lu               | 110 ms                                                                | 114 ms: 1.04x slower                                                 |
| float                    | 78.2 ms                                                               | 81.7 ms: 1.05x slower                                                |
| pyflate                  | 448 ms                                                                | 469 ms: 1.05x slower                                                 |
| crypto_pyaes             | 68.7 ms                                                               | 71.8 ms: 1.05x slower                                                |
| typing_runtime_protocols | 140 us                                                                | 147 us: 1.05x slower                                                 |
| go                       | 138 ms                                                                | 145 ms: 1.05x slower                                                 |
| deepcopy_memo            | 36.9 us                                                               | 38.8 us: 1.05x slower                                                |
| meteor_contest           | 106 ms                                                                | 111 ms: 1.05x slower                                                 |
| regex_compile            | 134 ms                                                                | 141 ms: 1.05x slower                                                 |
| fannkuch                 | 382 ms                                                                | 402 ms: 1.05x slower                                                 |
| spectral_norm            | 106 ms                                                                | 112 ms: 1.05x slower                                                 |
| async_generators         | 445 ms                                                                | 470 ms: 1.06x slower                                                 |
| chaos                    | 59.1 ms                                                               | 62.6 ms: 1.06x slower                                                |
| mako                     | 10.5 ms                                                               | 11.2 ms: 1.06x slower                                                |
| tomli_loads              | 2.02 sec                                                              | 2.15 sec: 1.06x slower                                               |
| unpickle_pure_python     | 212 us                                                                | 228 us: 1.08x slower                                                 |
| nbody                    | 88.7 ms                                                               | 95.5 ms: 1.08x slower                                                |
| mdp                      | 2.57 sec                                                              | 2.78 sec: 1.08x slower                                               |
| nqueens                  | 79.4 ms                                                               | 87.9 ms: 1.11x slower                                                |
| comprehensions           | 20.7 us                                                               | 23.0 us: 1.11x slower                                                |
| hexiom                   | 5.96 ms                                                               | 6.86 ms: 1.15x slower                                                |
| unpack_sequence          | 43.8 ns                                                               | 51.7 ns: 1.18x slower                                                |
| Geometric mean           | (ref)                                                                 | 1.03x slower                                                         |

Benchmark hidden because not significant (7): unpickle, bench_mp_pool, xml_etree_parse, async_tree_cpu_io_mixed, richards, async_tree_memoization, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
