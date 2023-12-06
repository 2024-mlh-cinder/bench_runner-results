
# Results vs. 3.12.0

- fork: python
- ref: fbfec5642edd9d7690bb
- machine: linux-x86_64
- commit hash: fbfec56
- commit date: 2023-09-26
- overall geometric mean: 1.00x faster
- HPT reliability: 76.25%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                |
| tornado_http   | 99.6 ms                                                | 95.7 ms: 1.04x faster                                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.5 ms: 1.02x faster                                                 |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                  |
| nbody          | 88.8 ms                                                | 90.8 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 134 ms: 1.07x faster                                                  |
| regex_effbot   | 3.55 ms                                                | 3.52 ms: 1.01x faster                                                 |
| regex_dna      | 209 ms                                                 | 212 ms: 1.01x slower                                                  |
| regex_v8       | 22.3 ms                                                | 24.3 ms: 1.09x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.06 sec: 1.08x faster                                                |
| pickle_pure_python   | 309 us                                                 | 295 us: 1.05x faster                                                  |
| unpickle_list        | 4.95 us                                                | 4.77 us: 1.04x faster                                                 |
| unpickle_pure_python | 218 us                                                 | 214 us: 1.02x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                  |
| pickle_list          | 4.62 us                                                | 4.59 us: 1.00x faster                                                 |
| xml_etree_parse      | 154 ms                                                 | 155 ms: 1.01x slower                                                  |
| xml_etree_process    | 58.6 ms                                                | 59.2 ms: 1.01x slower                                                 |
| xml_etree_generate   | 84.8 ms                                                | 86.5 ms: 1.02x slower                                                 |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                                 |
| pickle_dict          | 31.6 us                                                | 33.3 us: 1.05x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (3): unpickle, json_loads, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                 |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| raytrace                 | 294 ms                                                 | 266 ms: 1.11x faster                                                  |
| crypto_pyaes             | 77.2 ms                                                | 70.1 ms: 1.10x faster                                                 |
| coverage                 | 94.2 ms                                                | 85.7 ms: 1.10x faster                                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 65.6 ms: 1.08x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 2.06 sec: 1.08x faster                                                |
| regex_compile            | 144 ms                                                 | 134 ms: 1.07x faster                                                  |
| async_tree_none          | 469 ms                                                 | 438 ms: 1.07x faster                                                  |
| deltablue                | 3.52 ms                                                | 3.29 ms: 1.07x faster                                                 |
| scimark_sor              | 125 ms                                                 | 118 ms: 1.06x faster                                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.51 ms: 1.05x faster                                                 |
| chaos                    | 63.5 ms                                                | 60.5 ms: 1.05x faster                                                 |
| pickle_pure_python       | 309 us                                                 | 295 us: 1.05x faster                                                  |
| tornado_http             | 99.6 ms                                                | 95.7 ms: 1.04x faster                                                 |
| generators               | 31.1 ms                                                | 29.9 ms: 1.04x faster                                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.27 ms: 1.04x faster                                                 |
| asyncio_tcp              | 526 ms                                                 | 507 ms: 1.04x faster                                                  |
| unpickle_list            | 4.95 us                                                | 4.77 us: 1.04x faster                                                 |
| nqueens                  | 81.1 ms                                                | 78.4 ms: 1.03x faster                                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.59 ms: 1.03x faster                                                 |
| docutils                 | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                |
| typing_runtime_protocols | 146 us                                                 | 142 us: 1.03x faster                                                  |
| scimark_lu               | 114 ms                                                 | 111 ms: 1.03x faster                                                  |
| dulwich_log              | 67.9 ms                                                | 66.3 ms: 1.02x faster                                                 |
| bench_thread_pool        | 827 us                                                 | 808 us: 1.02x faster                                                  |
| hexiom                   | 6.12 ms                                                | 6.00 ms: 1.02x faster                                                 |
| unpickle_pure_python     | 218 us                                                 | 214 us: 1.02x faster                                                  |
| logging_format           | 6.90 us                                                | 6.77 us: 1.02x faster                                                 |
| async_tree_memoization   | 573 ms                                                 | 564 ms: 1.02x faster                                                  |
| mypy2                    | 344 ms                                                 | 338 ms: 1.02x faster                                                  |
| float                    | 80.7 ms                                                | 79.5 ms: 1.02x faster                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.48 sec: 1.02x faster                                                |
| pprint_safe_repr         | 735 ms                                                 | 724 ms: 1.01x faster                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                  |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                  |
| deepcopy                 | 355 us                                                 | 352 us: 1.01x faster                                                  |
| logging_simple           | 6.18 us                                                | 6.12 us: 1.01x faster                                                 |
| regex_effbot             | 3.55 ms                                                | 3.52 ms: 1.01x faster                                                 |
| comprehensions           | 20.4 us                                                | 20.3 us: 1.01x faster                                                 |
| pickle_list              | 4.62 us                                                | 4.59 us: 1.00x faster                                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                 |
| sqlglot_optimize         | 53.3 ms                                                | 53.2 ms: 1.00x faster                                                 |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                  |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                                |
| deepcopy_reduce          | 3.14 us                                                | 3.15 us: 1.01x slower                                                 |
| xml_etree_parse          | 154 ms                                                 | 155 ms: 1.01x slower                                                  |
| xml_etree_process        | 58.6 ms                                                | 59.2 ms: 1.01x slower                                                 |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                 |
| pyflate                  | 450 ms                                                 | 456 ms: 1.01x slower                                                  |
| unpack_sequence          | 44.8 ns                                                | 45.5 ns: 1.01x slower                                                 |
| regex_dna                | 209 ms                                                 | 212 ms: 1.01x slower                                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.54 ms: 1.01x slower                                                 |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                 |
| meteor_contest           | 105 ms                                                 | 107 ms: 1.02x slower                                                  |
| xml_etree_generate       | 84.8 ms                                                | 86.5 ms: 1.02x slower                                                 |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                                 |
| nbody                    | 88.8 ms                                                | 90.8 ms: 1.02x slower                                                 |
| async_generators         | 440 ms                                                 | 451 ms: 1.03x slower                                                  |
| go                       | 136 ms                                                 | 139 ms: 1.03x slower                                                  |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                |
| logging_silent           | 99.1 ns                                                | 102 ns: 1.03x slower                                                  |
| mdp                      | 2.57 sec                                               | 2.64 sec: 1.03x slower                                                |
| gc_traversal             | 3.84 ms                                                | 3.98 ms: 1.04x slower                                                 |
| pycparser                | 1.15 sec                                               | 1.19 sec: 1.04x slower                                                |
| json                     | 4.77 ms                                                | 4.98 ms: 1.04x slower                                                 |
| pickle_dict              | 31.6 us                                                | 33.3 us: 1.05x slower                                                 |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                 |
| regex_v8                 | 22.3 ms                                                | 24.3 ms: 1.09x slower                                                 |
| richards_super           | 49.0 ms                                                | 55.3 ms: 1.13x slower                                                 |
| richards                 | 43.2 ms                                                | 48.8 ms: 1.13x slower                                                 |
| telco                    | 6.87 ms                                                | 7.99 ms: 1.16x slower                                                 |
| dask                     | 365 ms                                                 | 525 ms: 1.44x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                          |

Benchmark hidden because not significant (11): async_tree_cpu_io_mixed, unpickle, sqlite_synth, deepcopy_memo, json_loads, scimark_fft, coroutines, bench_mp_pool, spectral_norm, fannkuch, json_dumps
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 76.25% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
