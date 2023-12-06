
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 28351a0
- commit date: 2023-09-22
- overall geometric mean: 1.02x slower
- HPT reliability: 96.41%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| tornado_http   | 99.6 ms                                                | 97.0 ms: 1.03x faster                                         |
| Geometric mean | (ref)                                                  | 1.01x faster                                                  |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                          |
| nbody          | 88.8 ms                                                | 90.1 ms: 1.01x slower                                         |
| float          | 80.7 ms                                                | 83.0 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                  | 1.02x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 207 ms: 1.01x faster                                          |
| regex_effbot   | 3.55 ms                                                | 3.53 ms: 1.00x faster                                         |
| regex_v8       | 22.3 ms                                                | 23.5 ms: 1.05x slower                                         |
| Geometric mean | (ref)                                                  | 1.01x slower                                                  |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.07 sec: 1.07x faster                                        |
| pickle_pure_python   | 309 us                                                 | 300 us: 1.03x faster                                          |
| unpickle             | 15.0 us                                                | 14.6 us: 1.03x faster                                         |
| pickle               | 10.6 us                                                | 10.4 us: 1.02x faster                                         |
| xml_etree_process    | 58.6 ms                                                | 57.6 ms: 1.02x faster                                         |
| json_loads           | 25.2 us                                                | 24.9 us: 1.02x faster                                         |
| json_dumps           | 9.85 ms                                                | 9.76 ms: 1.01x faster                                         |
| unpickle_list        | 4.95 us                                                | 4.91 us: 1.01x faster                                         |
| xml_etree_generate   | 84.8 ms                                                | 84.2 ms: 1.01x faster                                         |
| pickle_dict          | 31.6 us                                                | 32.0 us: 1.01x slower                                         |
| pickle_list          | 4.62 us                                                | 4.82 us: 1.04x slower                                         |
| unpickle_pure_python | 218 us                                                 | 228 us: 1.05x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                  |

Benchmark hidden because not significant (2): xml_etree_parse, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.89 ms: 1.00x faster                                         |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                         |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.1 ms: 1.04x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230922-linux-x86_64-brandtbucher-justin-3.13.0a0-28351a0 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 84.9 ms: 1.11x faster                                         |
| generators               | 31.1 ms                                                | 28.5 ms: 1.09x faster                                         |
| crypto_pyaes             | 77.2 ms                                                | 71.1 ms: 1.09x faster                                         |
| tomli_loads              | 2.22 sec                                               | 2.07 sec: 1.07x faster                                        |
| raytrace                 | 294 ms                                                 | 276 ms: 1.07x faster                                          |
| async_tree_none          | 469 ms                                                 | 443 ms: 1.06x faster                                          |
| asyncio_tcp              | 526 ms                                                 | 502 ms: 1.05x faster                                          |
| coroutines               | 22.4 ms                                                | 21.7 ms: 1.04x faster                                         |
| scimark_fft              | 358 ms                                                 | 347 ms: 1.03x faster                                          |
| scimark_monte_carlo      | 71.0 ms                                                | 68.8 ms: 1.03x faster                                         |
| pickle_pure_python       | 309 us                                                 | 300 us: 1.03x faster                                          |
| unpickle                 | 15.0 us                                                | 14.6 us: 1.03x faster                                         |
| deltablue                | 3.52 ms                                                | 3.42 ms: 1.03x faster                                         |
| tornado_http             | 99.6 ms                                                | 97.0 ms: 1.03x faster                                         |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.03x faster                                         |
| pickle                   | 10.6 us                                                | 10.4 us: 1.02x faster                                         |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                         |
| xml_etree_process        | 58.6 ms                                                | 57.6 ms: 1.02x faster                                         |
| json_loads               | 25.2 us                                                | 24.9 us: 1.02x faster                                         |
| logging_format           | 6.90 us                                                | 6.81 us: 1.01x faster                                         |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                          |
| json_dumps               | 9.85 ms                                                | 9.76 ms: 1.01x faster                                         |
| regex_dna                | 209 ms                                                 | 207 ms: 1.01x faster                                          |
| unpickle_list            | 4.95 us                                                | 4.91 us: 1.01x faster                                         |
| xml_etree_generate       | 84.8 ms                                                | 84.2 ms: 1.01x faster                                         |
| regex_effbot             | 3.55 ms                                                | 3.53 ms: 1.00x faster                                         |
| python_startup_no_site   | 6.90 ms                                                | 6.89 ms: 1.00x faster                                         |
| pprint_safe_repr         | 735 ms                                                 | 738 ms: 1.00x slower                                          |
| create_gc_cycles         | 1.52 ms                                                | 1.53 ms: 1.01x slower                                         |
| sqlite_synth             | 2.76 us                                                | 2.78 us: 1.01x slower                                         |
| mdp                      | 2.57 sec                                               | 2.58 sec: 1.01x slower                                        |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.81 sec: 1.01x slower                                        |
| dulwich_log              | 67.9 ms                                                | 68.4 ms: 1.01x slower                                         |
| deepcopy_reduce          | 3.14 us                                                | 3.16 us: 1.01x slower                                         |
| pprint_pformat           | 1.50 sec                                               | 1.52 sec: 1.01x slower                                        |
| sqlglot_optimize         | 53.3 ms                                                | 53.9 ms: 1.01x slower                                         |
| bench_thread_pool        | 827 us                                                 | 837 us: 1.01x slower                                          |
| pickle_dict              | 31.6 us                                                | 32.0 us: 1.01x slower                                         |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                          |
| nbody                    | 88.8 ms                                                | 90.1 ms: 1.01x slower                                         |
| typing_runtime_protocols | 146 us                                                 | 148 us: 1.02x slower                                          |
| spectral_norm            | 106 ms                                                 | 108 ms: 1.02x slower                                          |
| pycparser                | 1.15 sec                                               | 1.17 sec: 1.02x slower                                        |
| mypy2                    | 344 ms                                                 | 352 ms: 1.02x slower                                          |
| float                    | 80.7 ms                                                | 83.0 ms: 1.03x slower                                         |
| json                     | 4.77 ms                                                | 4.90 ms: 1.03x slower                                         |
| pyflate                  | 450 ms                                                 | 464 ms: 1.03x slower                                          |
| chaos                    | 63.5 ms                                                | 65.8 ms: 1.03x slower                                         |
| mako                     | 10.7 ms                                                | 11.1 ms: 1.04x slower                                         |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.04x slower                                        |
| pickle_list              | 4.62 us                                                | 4.82 us: 1.04x slower                                         |
| async_generators         | 440 ms                                                 | 460 ms: 1.04x slower                                          |
| fannkuch                 | 387 ms                                                 | 405 ms: 1.05x slower                                          |
| unpickle_pure_python     | 218 us                                                 | 228 us: 1.05x slower                                          |
| meteor_contest           | 105 ms                                                 | 110 ms: 1.05x slower                                          |
| deepcopy_memo            | 37.4 us                                                | 39.2 us: 1.05x slower                                         |
| logging_silent           | 99.1 ns                                                | 104 ns: 1.05x slower                                          |
| regex_v8                 | 22.3 ms                                                | 23.5 ms: 1.05x slower                                         |
| unpack_sequence          | 44.8 ns                                                | 47.5 ns: 1.06x slower                                         |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                         |
| nqueens                  | 81.1 ms                                                | 87.1 ms: 1.07x slower                                         |
| go                       | 136 ms                                                 | 148 ms: 1.09x slower                                          |
| richards_super           | 49.0 ms                                                | 53.6 ms: 1.09x slower                                         |
| richards                 | 43.2 ms                                                | 47.4 ms: 1.10x slower                                         |
| hexiom                   | 6.12 ms                                                | 6.84 ms: 1.12x slower                                         |
| gc_traversal             | 3.84 ms                                                | 4.36 ms: 1.13x slower                                         |
| comprehensions           | 20.4 us                                                | 23.3 us: 1.14x slower                                         |
| telco                    | 6.87 ms                                                | 8.16 ms: 1.19x slower                                         |
| dask                     | 365 ms                                                 | 533 ms: 1.46x slower                                          |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                  |

Benchmark hidden because not significant (13): async_tree_memoization, async_tree_cpu_io_mixed, xml_etree_parse, xml_etree_iterparse, logging_simple, docutils, pathlib, bench_mp_pool, regex_compile, deepcopy, sqlglot_normalize, scimark_lu, scimark_sparse_mat_mult
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 96.41% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
