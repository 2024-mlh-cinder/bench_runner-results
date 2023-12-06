
# Results vs. 3.12.0

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 0ad7112
- commit date: 2023-08-12
- overall geometric mean: 1.00x faster
- HPT reliability: 98.80%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.63 sec: 1.03x faster                                         |
| tornado_http   | 99.6 ms                                                | 95.7 ms: 1.04x faster                                          |
| Geometric mean | (ref)                                                  | 1.03x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 80.7 ms                                                | 80.2 ms: 1.01x faster                                          |
| nbody          | 88.8 ms                                                | 91.6 ms: 1.03x slower                                          |
| pidigits       | 187 ms                                                 | 196 ms: 1.05x slower                                           |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 135 ms: 1.06x faster                                           |
| regex_effbot   | 3.55 ms                                                | 3.57 ms: 1.01x slower                                          |
| regex_dna      | 209 ms                                                 | 227 ms: 1.09x slower                                           |
| regex_v8       | 22.3 ms                                                | 25.1 ms: 1.12x slower                                          |
| Geometric mean | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.11 sec: 1.05x faster                                         |
| xml_etree_process    | 58.6 ms                                                | 56.7 ms: 1.03x faster                                          |
| xml_etree_generate   | 84.8 ms                                                | 82.5 ms: 1.03x faster                                          |
| unpickle_pure_python | 218 us                                                 | 213 us: 1.02x faster                                           |
| pickle_pure_python   | 309 us                                                 | 303 us: 1.02x faster                                           |
| unpickle_list        | 4.95 us                                                | 4.85 us: 1.02x faster                                          |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                           |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                           |
| json_dumps           | 9.85 ms                                                | 9.78 ms: 1.01x faster                                          |
| pickle_dict          | 31.6 us                                                | 32.2 us: 1.02x slower                                          |
| pickle               | 10.6 us                                                | 10.9 us: 1.02x slower                                          |
| pickle_list          | 4.62 us                                                | 4.75 us: 1.03x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (2): json_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.56 ms: 1.01x slower                                          |
| python_startup_no_site | 6.90 ms                                                | 7.00 ms: 1.01x slower                                          |
| Geometric mean         | (ref)                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-brandtbucher-call_kw-3.13.0a0-0ad7112 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 67.8 ms: 1.14x faster                                          |
| coverage                 | 94.2 ms                                                | 86.7 ms: 1.09x faster                                          |
| asyncio_tcp              | 526 ms                                                 | 485 ms: 1.08x faster                                           |
| async_tree_none          | 469 ms                                                 | 437 ms: 1.07x faster                                           |
| deltablue                | 3.52 ms                                                | 3.28 ms: 1.07x faster                                          |
| logging_format           | 6.90 us                                                | 6.44 us: 1.07x faster                                          |
| generators               | 31.1 ms                                                | 29.0 ms: 1.07x faster                                          |
| raytrace                 | 294 ms                                                 | 275 ms: 1.07x faster                                           |
| chaos                    | 63.5 ms                                                | 59.5 ms: 1.07x faster                                          |
| regex_compile            | 144 ms                                                 | 135 ms: 1.06x faster                                           |
| scimark_monte_carlo      | 71.0 ms                                                | 66.9 ms: 1.06x faster                                          |
| tomli_loads              | 2.22 sec                                               | 2.11 sec: 1.05x faster                                         |
| scimark_sor              | 125 ms                                                 | 119 ms: 1.05x faster                                           |
| sqlglot_parse            | 1.32 ms                                                | 1.26 ms: 1.05x faster                                          |
| sqlglot_transpile        | 1.64 ms                                                | 1.57 ms: 1.05x faster                                          |
| sqlglot_normalize        | 107 ms                                                 | 103 ms: 1.04x faster                                           |
| tornado_http             | 99.6 ms                                                | 95.7 ms: 1.04x faster                                          |
| hexiom                   | 6.12 ms                                                | 5.90 ms: 1.04x faster                                          |
| scimark_lu               | 114 ms                                                 | 110 ms: 1.03x faster                                           |
| xml_etree_process        | 58.6 ms                                                | 56.7 ms: 1.03x faster                                          |
| logging_simple           | 6.18 us                                                | 5.99 us: 1.03x faster                                          |
| docutils                 | 2.70 sec                                               | 2.63 sec: 1.03x faster                                         |
| xml_etree_generate       | 84.8 ms                                                | 82.5 ms: 1.03x faster                                          |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.62 ms: 1.03x faster                                          |
| typing_runtime_protocols | 146 us                                                 | 142 us: 1.03x faster                                           |
| sqlglot_optimize         | 53.3 ms                                                | 52.0 ms: 1.03x faster                                          |
| spectral_norm            | 106 ms                                                 | 104 ms: 1.03x faster                                           |
| unpickle_pure_python     | 218 us                                                 | 213 us: 1.02x faster                                           |
| pprint_pformat           | 1.50 sec                                               | 1.47 sec: 1.02x faster                                         |
| deepcopy                 | 355 us                                                 | 348 us: 1.02x faster                                           |
| pickle_pure_python       | 309 us                                                 | 303 us: 1.02x faster                                           |
| unpickle_list            | 4.95 us                                                | 4.85 us: 1.02x faster                                          |
| nqueens                  | 81.1 ms                                                | 79.6 ms: 1.02x faster                                          |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 701 ms: 1.02x faster                                           |
| pprint_safe_repr         | 735 ms                                                 | 721 ms: 1.02x faster                                           |
| bench_thread_pool        | 827 us                                                 | 814 us: 1.02x faster                                           |
| fannkuch                 | 387 ms                                                 | 382 ms: 1.01x faster                                           |
| mypy2                    | 344 ms                                                 | 339 ms: 1.01x faster                                           |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                           |
| dulwich_log              | 67.9 ms                                                | 67.0 ms: 1.01x faster                                          |
| async_tree_memoization   | 573 ms                                                 | 566 ms: 1.01x faster                                           |
| scimark_fft              | 358 ms                                                 | 355 ms: 1.01x faster                                           |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                          |
| pyflate                  | 450 ms                                                 | 446 ms: 1.01x faster                                           |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                           |
| json_dumps               | 9.85 ms                                                | 9.78 ms: 1.01x faster                                          |
| float                    | 80.7 ms                                                | 80.2 ms: 1.01x faster                                          |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                         |
| mdp                      | 2.57 sec                                               | 2.57 sec: 1.00x slower                                         |
| regex_effbot             | 3.55 ms                                                | 3.57 ms: 1.01x slower                                          |
| python_startup           | 9.47 ms                                                | 9.56 ms: 1.01x slower                                          |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                          |
| python_startup_no_site   | 6.90 ms                                                | 7.00 ms: 1.01x slower                                          |
| meteor_contest           | 105 ms                                                 | 107 ms: 1.02x slower                                           |
| comprehensions           | 20.4 us                                                | 20.8 us: 1.02x slower                                          |
| pickle_dict              | 31.6 us                                                | 32.2 us: 1.02x slower                                          |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.02x slower                                          |
| async_generators         | 440 ms                                                 | 451 ms: 1.02x slower                                           |
| pickle                   | 10.6 us                                                | 10.9 us: 1.02x slower                                          |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                         |
| logging_silent           | 99.1 ns                                                | 102 ns: 1.03x slower                                           |
| pickle_list              | 4.62 us                                                | 4.75 us: 1.03x slower                                          |
| go                       | 136 ms                                                 | 140 ms: 1.03x slower                                           |
| nbody                    | 88.8 ms                                                | 91.6 ms: 1.03x slower                                          |
| json                     | 4.77 ms                                                | 4.93 ms: 1.03x slower                                          |
| coroutines               | 22.4 ms                                                | 23.2 ms: 1.03x slower                                          |
| pycparser                | 1.15 sec                                               | 1.20 sec: 1.05x slower                                         |
| pidigits                 | 187 ms                                                 | 196 ms: 1.05x slower                                           |
| unpack_sequence          | 44.8 ns                                                | 48.7 ns: 1.09x slower                                          |
| richards_super           | 49.0 ms                                                | 53.3 ms: 1.09x slower                                          |
| regex_dna                | 209 ms                                                 | 227 ms: 1.09x slower                                           |
| richards                 | 43.2 ms                                                | 47.1 ms: 1.09x slower                                          |
| gc_traversal             | 3.84 ms                                                | 4.31 ms: 1.12x slower                                          |
| regex_v8                 | 22.3 ms                                                | 25.1 ms: 1.12x slower                                          |
| telco                    | 6.87 ms                                                | 7.91 ms: 1.15x slower                                          |
| dask                     | 365 ms                                                 | 525 ms: 1.44x slower                                           |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (6): sqlite_synth, json_loads, deepcopy_reduce, deepcopy_memo, bench_mp_pool, unpickle
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.80% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
