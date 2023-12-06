
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| tornado_http   | 99.6 ms                                                | 97.4 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                  | 1.01x faster                                                  |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                          |
| float          | 80.7 ms                                                | 83.9 ms: 1.04x slower                                         |
| nbody          | 88.8 ms                                                | 100 ms: 1.13x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 146 ms: 1.02x slower                                          |
| regex_effbot   | 3.55 ms                                                | 3.67 ms: 1.03x slower                                         |
| regex_dna      | 209 ms                                                 | 225 ms: 1.08x slower                                          |
| regex_v8       | 22.3 ms                                                | 24.8 ms: 1.11x slower                                         |
| Geometric mean | (ref)                                                  | 1.06x slower                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.3 us: 1.05x faster                                         |
| pickle_pure_python   | 309 us                                                 | 301 us: 1.03x faster                                          |
| xml_etree_process    | 58.6 ms                                                | 57.4 ms: 1.02x faster                                         |
| xml_etree_generate   | 84.8 ms                                                | 83.3 ms: 1.02x faster                                         |
| pickle_dict          | 31.6 us                                                | 31.2 us: 1.01x faster                                         |
| unpickle_list        | 4.95 us                                                | 4.89 us: 1.01x faster                                         |
| json_loads           | 25.2 us                                                | 25.4 us: 1.01x slower                                         |
| json_dumps           | 9.85 ms                                                | 9.94 ms: 1.01x slower                                         |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                          |
| pickle               | 10.6 us                                                | 10.9 us: 1.02x slower                                         |
| tomli_loads          | 2.22 sec                                               | 2.29 sec: 1.03x slower                                        |
| unpickle_pure_python | 218 us                                                 | 231 us: 1.06x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (2): pickle_list, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.50 ms: 1.00x slower                                         |
| python_startup_no_site | 6.90 ms                                                | 6.99 ms: 1.01x slower                                         |
| Geometric mean         | (ref)                                                  | 1.01x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.3 ms: 1.06x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 86.6 ms: 1.09x faster                                         |
| crypto_pyaes             | 77.2 ms                                                | 72.2 ms: 1.07x faster                                         |
| asyncio_tcp              | 526 ms                                                 | 493 ms: 1.07x faster                                          |
| unpickle                 | 15.0 us                                                | 14.3 us: 1.05x faster                                         |
| async_tree_none          | 469 ms                                                 | 447 ms: 1.05x faster                                          |
| logging_format           | 6.90 us                                                | 6.60 us: 1.05x faster                                         |
| scimark_monte_carlo      | 71.0 ms                                                | 68.1 ms: 1.04x faster                                         |
| logging_simple           | 6.18 us                                                | 5.93 us: 1.04x faster                                         |
| generators               | 31.1 ms                                                | 30.0 ms: 1.04x faster                                         |
| raytrace                 | 294 ms                                                 | 285 ms: 1.03x faster                                          |
| pickle_pure_python       | 309 us                                                 | 301 us: 1.03x faster                                          |
| tornado_http             | 99.6 ms                                                | 97.4 ms: 1.02x faster                                         |
| xml_etree_process        | 58.6 ms                                                | 57.4 ms: 1.02x faster                                         |
| xml_etree_generate       | 84.8 ms                                                | 83.3 ms: 1.02x faster                                         |
| pickle_dict              | 31.6 us                                                | 31.2 us: 1.01x faster                                         |
| unpickle_list            | 4.95 us                                                | 4.89 us: 1.01x faster                                         |
| deltablue                | 3.52 ms                                                | 3.48 ms: 1.01x faster                                         |
| sqlglot_parse            | 1.32 ms                                                | 1.31 ms: 1.01x faster                                         |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                          |
| sqlglot_transpile        | 1.64 ms                                                | 1.63 ms: 1.01x faster                                         |
| coroutines               | 22.4 ms                                                | 22.3 ms: 1.01x faster                                         |
| deepcopy_reduce          | 3.14 us                                                | 3.12 us: 1.01x faster                                         |
| deepcopy                 | 355 us                                                 | 354 us: 1.00x faster                                          |
| create_gc_cycles         | 1.52 ms                                                | 1.52 ms: 1.00x faster                                         |
| python_startup           | 9.47 ms                                                | 9.50 ms: 1.00x slower                                         |
| json_loads               | 25.2 us                                                | 25.4 us: 1.01x slower                                         |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                          |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.01x slower                                         |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                          |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.81 sec: 1.01x slower                                        |
| json_dumps               | 9.85 ms                                                | 9.94 ms: 1.01x slower                                         |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                          |
| dulwich_log              | 67.9 ms                                                | 68.6 ms: 1.01x slower                                         |
| python_startup_no_site   | 6.90 ms                                                | 6.99 ms: 1.01x slower                                         |
| json                     | 4.77 ms                                                | 4.84 ms: 1.02x slower                                         |
| regex_compile            | 144 ms                                                 | 146 ms: 1.02x slower                                          |
| bench_thread_pool        | 827 us                                                 | 841 us: 1.02x slower                                          |
| sqlglot_optimize         | 53.3 ms                                                | 54.4 ms: 1.02x slower                                         |
| pathlib                  | 18.5 ms                                                | 18.9 ms: 1.02x slower                                         |
| unpack_sequence          | 44.8 ns                                                | 45.8 ns: 1.02x slower                                         |
| pprint_safe_repr         | 735 ms                                                 | 752 ms: 1.02x slower                                          |
| pprint_pformat           | 1.50 sec                                               | 1.54 sec: 1.02x slower                                        |
| pickle                   | 10.6 us                                                | 10.9 us: 1.02x slower                                         |
| mypy2                    | 344 ms                                                 | 354 ms: 1.03x slower                                          |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.88 ms: 1.03x slower                                         |
| tomli_loads              | 2.22 sec                                               | 2.29 sec: 1.03x slower                                        |
| regex_effbot             | 3.55 ms                                                | 3.67 ms: 1.03x slower                                         |
| float                    | 80.7 ms                                                | 83.9 ms: 1.04x slower                                         |
| chaos                    | 63.5 ms                                                | 66.0 ms: 1.04x slower                                         |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.04x slower                                        |
| typing_runtime_protocols | 146 us                                                 | 152 us: 1.04x slower                                          |
| spectral_norm            | 106 ms                                                 | 112 ms: 1.05x slower                                          |
| scimark_fft              | 358 ms                                                 | 377 ms: 1.05x slower                                          |
| mako                     | 10.7 ms                                                | 11.3 ms: 1.06x slower                                         |
| unpickle_pure_python     | 218 us                                                 | 231 us: 1.06x slower                                          |
| async_generators         | 440 ms                                                 | 469 ms: 1.06x slower                                          |
| pyflate                  | 450 ms                                                 | 481 ms: 1.07x slower                                          |
| deepcopy_memo            | 37.4 us                                                | 40.0 us: 1.07x slower                                         |
| pycparser                | 1.15 sec                                               | 1.23 sec: 1.07x slower                                        |
| mdp                      | 2.57 sec                                               | 2.76 sec: 1.07x slower                                        |
| meteor_contest           | 105 ms                                                 | 113 ms: 1.07x slower                                          |
| logging_silent           | 99.1 ns                                                | 107 ns: 1.08x slower                                          |
| regex_dna                | 209 ms                                                 | 225 ms: 1.08x slower                                          |
| go                       | 136 ms                                                 | 150 ms: 1.11x slower                                          |
| regex_v8                 | 22.3 ms                                                | 24.8 ms: 1.11x slower                                         |
| fannkuch                 | 387 ms                                                 | 429 ms: 1.11x slower                                          |
| nbody                    | 88.8 ms                                                | 100 ms: 1.13x slower                                          |
| richards_super           | 49.0 ms                                                | 55.6 ms: 1.13x slower                                         |
| richards                 | 43.2 ms                                                | 49.6 ms: 1.15x slower                                         |
| nqueens                  | 81.1 ms                                                | 94.2 ms: 1.16x slower                                         |
| hexiom                   | 6.12 ms                                                | 7.15 ms: 1.17x slower                                         |
| comprehensions           | 20.4 us                                                | 24.1 us: 1.18x slower                                         |
| telco                    | 6.87 ms                                                | 8.20 ms: 1.19x slower                                         |
| dask                     | 365 ms                                                 | 534 ms: 1.46x slower                                          |
| Geometric mean           | (ref)                                                  | 1.03x slower                                                  |

Benchmark hidden because not significant (8): bench_mp_pool, async_tree_cpu_io_mixed, scimark_lu, docutils, sqlite_synth, pickle_list, xml_etree_parse, async_tree_memoization
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
