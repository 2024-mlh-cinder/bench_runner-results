
# Results vs. 3.12.0

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 9c8ccf6
- commit date: 2023-09-05
- overall geometric mean: 1.01x faster
- HPT reliability: 98.05%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.63 sec: 1.03x faster                                         |
| tornado_http   | 99.6 ms                                                | 95.3 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.04x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.1 ms: 1.02x faster                                          |
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                           |
| nbody          | 88.8 ms                                                | 92.3 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 135 ms: 1.07x faster                                           |
| regex_effbot   | 3.55 ms                                                | 3.74 ms: 1.06x slower                                          |
| regex_dna      | 209 ms                                                 | 220 ms: 1.06x slower                                           |
| regex_v8       | 22.3 ms                                                | 24.6 ms: 1.10x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 294 us: 1.05x faster                                           |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                         |
| xml_etree_generate   | 84.8 ms                                                | 81.3 ms: 1.04x faster                                          |
| xml_etree_process    | 58.6 ms                                                | 56.4 ms: 1.04x faster                                          |
| unpickle_pure_python | 218 us                                                 | 210 us: 1.04x faster                                           |
| unpickle             | 15.0 us                                                | 14.5 us: 1.03x faster                                          |
| xml_etree_iterparse  | 104 ms                                                 | 101 ms: 1.02x faster                                           |
| xml_etree_parse      | 154 ms                                                 | 151 ms: 1.02x faster                                           |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                          |
| json_dumps           | 9.85 ms                                                | 9.75 ms: 1.01x faster                                          |
| pickle_dict          | 31.6 us                                                | 31.5 us: 1.01x faster                                          |
| pickle_list          | 4.62 us                                                | 4.66 us: 1.01x slower                                          |
| unpickle_list        | 4.95 us                                                | 5.06 us: 1.02x slower                                          |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                   |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.48 ms: 1.00x slower                                          |
| python_startup_no_site | 6.90 ms                                                | 6.97 ms: 1.01x slower                                          |
| Geometric mean         | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230905-linux-x86_64-brandtbucher-call_kw-3.13.0a0-9c8ccf6 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 68.5 ms: 1.13x faster                                          |
| chaos                    | 63.5 ms                                                | 58.7 ms: 1.08x faster                                          |
| coverage                 | 94.2 ms                                                | 87.0 ms: 1.08x faster                                          |
| deltablue                | 3.52 ms                                                | 3.26 ms: 1.08x faster                                          |
| scimark_monte_carlo      | 71.0 ms                                                | 65.8 ms: 1.08x faster                                          |
| raytrace                 | 294 ms                                                 | 273 ms: 1.08x faster                                           |
| asyncio_tcp              | 526 ms                                                 | 489 ms: 1.08x faster                                           |
| generators               | 31.1 ms                                                | 29.0 ms: 1.07x faster                                          |
| regex_compile            | 144 ms                                                 | 135 ms: 1.07x faster                                           |
| async_tree_none          | 469 ms                                                 | 440 ms: 1.07x faster                                           |
| logging_format           | 6.90 us                                                | 6.51 us: 1.06x faster                                          |
| scimark_sor              | 125 ms                                                 | 118 ms: 1.06x faster                                           |
| sqlglot_parse            | 1.32 ms                                                | 1.25 ms: 1.05x faster                                          |
| pickle_pure_python       | 309 us                                                 | 294 us: 1.05x faster                                           |
| sqlglot_transpile        | 1.64 ms                                                | 1.56 ms: 1.05x faster                                          |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                         |
| scimark_lu               | 114 ms                                                 | 109 ms: 1.05x faster                                           |
| tornado_http             | 99.6 ms                                                | 95.3 ms: 1.04x faster                                          |
| xml_etree_generate       | 84.8 ms                                                | 81.3 ms: 1.04x faster                                          |
| logging_simple           | 6.18 us                                                | 5.92 us: 1.04x faster                                          |
| sqlglot_normalize        | 107 ms                                                 | 103 ms: 1.04x faster                                           |
| xml_etree_process        | 58.6 ms                                                | 56.4 ms: 1.04x faster                                          |
| unpickle_pure_python     | 218 us                                                 | 210 us: 1.04x faster                                           |
| unpickle                 | 15.0 us                                                | 14.5 us: 1.03x faster                                          |
| fannkuch                 | 387 ms                                                 | 375 ms: 1.03x faster                                           |
| typing_runtime_protocols | 146 us                                                 | 142 us: 1.03x faster                                           |
| deepcopy                 | 355 us                                                 | 346 us: 1.03x faster                                           |
| hexiom                   | 6.12 ms                                                | 5.97 ms: 1.03x faster                                          |
| docutils                 | 2.70 sec                                               | 2.63 sec: 1.03x faster                                         |
| xml_etree_iterparse      | 104 ms                                                 | 101 ms: 1.02x faster                                           |
| sqlglot_optimize         | 53.3 ms                                                | 52.2 ms: 1.02x faster                                          |
| deepcopy_memo            | 37.4 us                                                | 36.6 us: 1.02x faster                                          |
| float                    | 80.7 ms                                                | 79.1 ms: 1.02x faster                                          |
| bench_thread_pool        | 827 us                                                 | 811 us: 1.02x faster                                           |
| mypy2                    | 344 ms                                                 | 338 ms: 1.02x faster                                           |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.02x faster                                           |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                          |
| nqueens                  | 81.1 ms                                                | 79.7 ms: 1.02x faster                                          |
| deepcopy_reduce          | 3.14 us                                                | 3.08 us: 1.02x faster                                          |
| pprint_pformat           | 1.50 sec                                               | 1.48 sec: 1.02x faster                                         |
| pprint_safe_repr         | 735 ms                                                 | 724 ms: 1.02x faster                                           |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                          |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 704 ms: 1.01x faster                                           |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                          |
| async_tree_memoization   | 573 ms                                                 | 566 ms: 1.01x faster                                           |
| dulwich_log              | 67.9 ms                                                | 67.2 ms: 1.01x faster                                          |
| json_dumps               | 9.85 ms                                                | 9.75 ms: 1.01x faster                                          |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                          |
| scimark_fft              | 358 ms                                                 | 356 ms: 1.01x faster                                           |
| pickle_dict              | 31.6 us                                                | 31.5 us: 1.01x faster                                          |
| python_startup           | 9.47 ms                                                | 9.48 ms: 1.00x slower                                          |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                         |
| pyflate                  | 450 ms                                                 | 452 ms: 1.00x slower                                           |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                           |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                           |
| pickle_list              | 4.62 us                                                | 4.66 us: 1.01x slower                                          |
| python_startup_no_site   | 6.90 ms                                                | 6.97 ms: 1.01x slower                                          |
| async_generators         | 440 ms                                                 | 447 ms: 1.02x slower                                           |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.02x slower                                          |
| unpickle_list            | 4.95 us                                                | 5.06 us: 1.02x slower                                          |
| comprehensions           | 20.4 us                                                | 21.0 us: 1.02x slower                                          |
| go                       | 136 ms                                                 | 139 ms: 1.03x slower                                           |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.89 ms: 1.03x slower                                          |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                         |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.03x slower                                           |
| nbody                    | 88.8 ms                                                | 92.3 ms: 1.04x slower                                          |
| json                     | 4.77 ms                                                | 4.96 ms: 1.04x slower                                          |
| pycparser                | 1.15 sec                                               | 1.20 sec: 1.04x slower                                         |
| regex_effbot             | 3.55 ms                                                | 3.74 ms: 1.06x slower                                          |
| regex_dna                | 209 ms                                                 | 220 ms: 1.06x slower                                           |
| gc_traversal             | 3.84 ms                                                | 4.08 ms: 1.06x slower                                          |
| richards                 | 43.2 ms                                                | 47.3 ms: 1.10x slower                                          |
| richards_super           | 49.0 ms                                                | 53.7 ms: 1.10x slower                                          |
| regex_v8                 | 22.3 ms                                                | 24.6 ms: 1.10x slower                                          |
| telco                    | 6.87 ms                                                | 7.96 ms: 1.16x slower                                          |
| dask                     | 365 ms                                                 | 519 ms: 1.42x slower                                           |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (6): spectral_norm, bench_mp_pool, mako, mdp, unpack_sequence, json_loads
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.05% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
