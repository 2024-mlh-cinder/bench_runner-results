
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 56976b3
- commit date: 2023-09-15
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| tornado_http   | 99.6 ms                                                | 97.6 ms: 1.02x faster                                         |
| Geometric mean | (ref)                                                  | 1.01x faster                                                  |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                          |
| float          | 80.7 ms                                                | 83.4 ms: 1.03x slower                                         |
| nbody          | 88.8 ms                                                | 118 ms: 1.33x slower                                          |
| Geometric mean | (ref)                                                  | 1.11x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.51 ms: 1.01x faster                                         |
| regex_compile  | 144 ms                                                 | 150 ms: 1.04x slower                                          |
| regex_v8       | 22.3 ms                                                | 24.2 ms: 1.08x slower                                         |
| Geometric mean | (ref)                                                  | 1.03x slower                                                  |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.0 us: 1.07x faster                                         |
| unpickle_list        | 4.95 us                                                | 4.73 us: 1.05x faster                                         |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                          |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                          |
| xml_etree_process    | 58.6 ms                                                | 58.1 ms: 1.01x faster                                         |
| xml_etree_generate   | 84.8 ms                                                | 84.4 ms: 1.01x faster                                         |
| pickle_dict          | 31.6 us                                                | 31.7 us: 1.00x slower                                         |
| json_dumps           | 9.85 ms                                                | 9.97 ms: 1.01x slower                                         |
| pickle               | 10.6 us                                                | 10.7 us: 1.01x slower                                         |
| pickle_list          | 4.62 us                                                | 4.70 us: 1.02x slower                                         |
| tomli_loads          | 2.22 sec                                               | 2.34 sec: 1.06x slower                                        |
| unpickle_pure_python | 218 us                                                 | 233 us: 1.07x slower                                          |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                  |

Benchmark hidden because not significant (2): pickle_pure_python, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.87 ms: 1.00x faster                                         |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                         |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.3 ms: 1.05x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin-3.13.0a0-56976b3 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 84.8 ms: 1.11x faster                                         |
| generators               | 31.1 ms                                                | 28.4 ms: 1.09x faster                                         |
| gc_traversal             | 3.84 ms                                                | 3.57 ms: 1.08x faster                                         |
| unpickle                 | 15.0 us                                                | 14.0 us: 1.07x faster                                         |
| asyncio_tcp              | 526 ms                                                 | 491 ms: 1.07x faster                                          |
| scimark_monte_carlo      | 71.0 ms                                                | 67.4 ms: 1.05x faster                                         |
| async_tree_none          | 469 ms                                                 | 449 ms: 1.05x faster                                          |
| unpickle_list            | 4.95 us                                                | 4.73 us: 1.05x faster                                         |
| raytrace                 | 294 ms                                                 | 284 ms: 1.04x faster                                          |
| crypto_pyaes             | 77.2 ms                                                | 75.6 ms: 1.02x faster                                         |
| tornado_http             | 99.6 ms                                                | 97.6 ms: 1.02x faster                                         |
| sqlglot_parse            | 1.32 ms                                                | 1.30 ms: 1.02x faster                                         |
| sqlglot_transpile        | 1.64 ms                                                | 1.62 ms: 1.01x faster                                         |
| regex_effbot             | 3.55 ms                                                | 3.51 ms: 1.01x faster                                         |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                          |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                         |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                          |
| xml_etree_process        | 58.6 ms                                                | 58.1 ms: 1.01x faster                                         |
| xml_etree_generate       | 84.8 ms                                                | 84.4 ms: 1.01x faster                                         |
| python_startup_no_site   | 6.90 ms                                                | 6.87 ms: 1.00x faster                                         |
| create_gc_cycles         | 1.52 ms                                                | 1.52 ms: 1.00x faster                                         |
| pickle_dict              | 31.6 us                                                | 31.7 us: 1.00x slower                                         |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.01x slower                                        |
| coroutines               | 22.4 ms                                                | 22.6 ms: 1.01x slower                                         |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                          |
| async_tree_memoization   | 573 ms                                                 | 579 ms: 1.01x slower                                          |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                          |
| json_dumps               | 9.85 ms                                                | 9.97 ms: 1.01x slower                                         |
| json                     | 4.77 ms                                                | 4.83 ms: 1.01x slower                                         |
| pickle                   | 10.6 us                                                | 10.7 us: 1.01x slower                                         |
| sqlglot_optimize         | 53.3 ms                                                | 54.0 ms: 1.01x slower                                         |
| pickle_list              | 4.62 us                                                | 4.70 us: 1.02x slower                                         |
| dulwich_log              | 67.9 ms                                                | 69.5 ms: 1.02x slower                                         |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.03x slower                                         |
| scimark_lu               | 114 ms                                                 | 117 ms: 1.03x slower                                          |
| bench_thread_pool        | 827 us                                                 | 854 us: 1.03x slower                                          |
| float                    | 80.7 ms                                                | 83.4 ms: 1.03x slower                                         |
| spectral_norm            | 106 ms                                                 | 110 ms: 1.03x slower                                          |
| mypy2                    | 344 ms                                                 | 356 ms: 1.04x slower                                          |
| regex_compile            | 144 ms                                                 | 150 ms: 1.04x slower                                          |
| pycparser                | 1.15 sec                                               | 1.20 sec: 1.04x slower                                        |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.05x slower                                        |
| deepcopy_reduce          | 3.14 us                                                | 3.30 us: 1.05x slower                                         |
| mako                     | 10.7 ms                                                | 11.3 ms: 1.05x slower                                         |
| tomli_loads              | 2.22 sec                                               | 2.34 sec: 1.06x slower                                        |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.02 ms: 1.06x slower                                         |
| async_generators         | 440 ms                                                 | 468 ms: 1.06x slower                                          |
| scimark_fft              | 358 ms                                                 | 381 ms: 1.06x slower                                          |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                         |
| unpickle_pure_python     | 218 us                                                 | 233 us: 1.07x slower                                          |
| deepcopy                 | 355 us                                                 | 382 us: 1.07x slower                                          |
| meteor_contest           | 105 ms                                                 | 113 ms: 1.08x slower                                          |
| logging_silent           | 99.1 ns                                                | 107 ns: 1.08x slower                                          |
| regex_v8                 | 22.3 ms                                                | 24.2 ms: 1.08x slower                                         |
| pprint_safe_repr         | 735 ms                                                 | 797 ms: 1.08x slower                                          |
| typing_runtime_protocols | 146 us                                                 | 159 us: 1.09x slower                                          |
| pprint_pformat           | 1.50 sec                                               | 1.64 sec: 1.09x slower                                        |
| mdp                      | 2.57 sec                                               | 2.83 sec: 1.10x slower                                        |
| pyflate                  | 450 ms                                                 | 500 ms: 1.11x slower                                          |
| go                       | 136 ms                                                 | 154 ms: 1.13x slower                                          |
| richards_super           | 49.0 ms                                                | 55.9 ms: 1.14x slower                                         |
| richards                 | 43.2 ms                                                | 49.3 ms: 1.14x slower                                         |
| fannkuch                 | 387 ms                                                 | 455 ms: 1.17x slower                                          |
| telco                    | 6.87 ms                                                | 8.08 ms: 1.18x slower                                         |
| comprehensions           | 20.4 us                                                | 24.3 us: 1.19x slower                                         |
| deepcopy_memo            | 37.4 us                                                | 45.1 us: 1.21x slower                                         |
| unpack_sequence          | 44.8 ns                                                | 54.7 ns: 1.22x slower                                         |
| hexiom                   | 6.12 ms                                                | 7.53 ms: 1.23x slower                                         |
| chaos                    | 63.5 ms                                                | 80.0 ms: 1.26x slower                                         |
| nqueens                  | 81.1 ms                                                | 104 ms: 1.28x slower                                          |
| nbody                    | 88.8 ms                                                | 118 ms: 1.33x slower                                          |
| dask                     | 365 ms                                                 | 538 ms: 1.47x slower                                          |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                  |

Benchmark hidden because not significant (10): logging_format, regex_dna, pickle_pure_python, bench_mp_pool, docutils, json_loads, scimark_sor, deltablue, async_tree_cpu_io_mixed, logging_simple
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
