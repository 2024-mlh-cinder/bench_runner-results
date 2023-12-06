
# Results vs. 3.12.0

- fork: brandtbucher
- ref: kwnames_tstate
- machine: linux-x86_64
- commit hash: 70d0242
- commit date: 2023-08-11
- overall geometric mean: 1.01x slower
- HPT reliability: 59.77%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.63 sec: 1.03x faster                                                |
| tornado_http   | 99.6 ms                                                | 96.5 ms: 1.03x faster                                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 81.4 ms: 1.01x slower                                                 |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                  |
| nbody          | 88.8 ms                                                | 96.1 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                  |
| regex_dna      | 209 ms                                                 | 219 ms: 1.05x slower                                                  |
| regex_effbot   | 3.55 ms                                                | 3.76 ms: 1.06x slower                                                 |
| regex_v8       | 22.3 ms                                                | 25.9 ms: 1.16x slower                                                 |
| Geometric mean | (ref)                                                  | 1.05x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|---------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpickle            | 15.0 us                                                | 14.4 us: 1.04x faster                                                 |
| pickle_pure_python  | 309 us                                                 | 303 us: 1.02x faster                                                  |
| pickle_list         | 4.62 us                                                | 4.54 us: 1.02x faster                                                 |
| xml_etree_process   | 58.6 ms                                                | 57.7 ms: 1.01x faster                                                 |
| xml_etree_generate  | 84.8 ms                                                | 83.7 ms: 1.01x faster                                                 |
| tomli_loads         | 2.22 sec                                               | 2.19 sec: 1.01x faster                                                |
| xml_etree_parse     | 154 ms                                                 | 152 ms: 1.01x faster                                                  |
| xml_etree_iterparse | 104 ms                                                 | 103 ms: 1.01x faster                                                  |
| json_dumps          | 9.85 ms                                                | 9.90 ms: 1.01x slower                                                 |
| unpickle_list       | 4.95 us                                                | 4.98 us: 1.01x slower                                                 |
| pickle_dict         | 31.6 us                                                | 31.9 us: 1.01x slower                                                 |
| pickle              | 10.6 us                                                | 10.9 us: 1.03x slower                                                 |
| Geometric mean      | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (2): unpickle_pure_python, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.41 ms: 1.01x faster                                                 |
| python_startup_no_site | 6.90 ms                                                | 6.88 ms: 1.00x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.00x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.2 ms: 1.04x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_tstate-3.13.0a0-70d0242 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 69.5 ms: 1.11x faster                                                 |
| coverage                 | 94.2 ms                                                | 85.7 ms: 1.10x faster                                                 |
| async_tree_none          | 469 ms                                                 | 442 ms: 1.06x faster                                                  |
| raytrace                 | 294 ms                                                 | 277 ms: 1.06x faster                                                  |
| deltablue                | 3.52 ms                                                | 3.32 ms: 1.06x faster                                                 |
| asyncio_tcp              | 526 ms                                                 | 499 ms: 1.05x faster                                                  |
| scimark_monte_carlo      | 71.0 ms                                                | 67.5 ms: 1.05x faster                                                 |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                  |
| chaos                    | 63.5 ms                                                | 60.5 ms: 1.05x faster                                                 |
| scimark_lu               | 114 ms                                                 | 109 ms: 1.04x faster                                                  |
| logging_format           | 6.90 us                                                | 6.62 us: 1.04x faster                                                 |
| unpickle                 | 15.0 us                                                | 14.4 us: 1.04x faster                                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                                 |
| logging_simple           | 6.18 us                                                | 5.98 us: 1.03x faster                                                 |
| tornado_http             | 99.6 ms                                                | 96.5 ms: 1.03x faster                                                 |
| generators               | 31.1 ms                                                | 30.2 ms: 1.03x faster                                                 |
| docutils                 | 2.70 sec                                               | 2.63 sec: 1.03x faster                                                |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.03x faster                                                 |
| pickle_pure_python       | 309 us                                                 | 303 us: 1.02x faster                                                  |
| sqlite_synth             | 2.76 us                                                | 2.71 us: 1.02x faster                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.47 sec: 1.02x faster                                                |
| pprint_safe_repr         | 735 ms                                                 | 722 ms: 1.02x faster                                                  |
| pickle_list              | 4.62 us                                                | 4.54 us: 1.02x faster                                                 |
| dulwich_log              | 67.9 ms                                                | 66.9 ms: 1.02x faster                                                 |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 704 ms: 1.01x faster                                                  |
| xml_etree_process        | 58.6 ms                                                | 57.7 ms: 1.01x faster                                                 |
| mypy2                    | 344 ms                                                 | 339 ms: 1.01x faster                                                  |
| xml_etree_generate       | 84.8 ms                                                | 83.7 ms: 1.01x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 2.19 sec: 1.01x faster                                                |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                  |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                  |
| nqueens                  | 81.1 ms                                                | 80.5 ms: 1.01x faster                                                 |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                                 |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                  |
| bench_thread_pool        | 827 us                                                 | 822 us: 1.01x faster                                                  |
| python_startup           | 9.47 ms                                                | 9.41 ms: 1.01x faster                                                 |
| deepcopy                 | 355 us                                                 | 354 us: 1.00x faster                                                  |
| sqlglot_optimize         | 53.3 ms                                                | 53.2 ms: 1.00x faster                                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.88 ms: 1.00x faster                                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                                |
| json_dumps               | 9.85 ms                                                | 9.90 ms: 1.01x slower                                                 |
| unpickle_list            | 4.95 us                                                | 4.98 us: 1.01x slower                                                 |
| pathlib                  | 18.5 ms                                                | 18.6 ms: 1.01x slower                                                 |
| float                    | 80.7 ms                                                | 81.4 ms: 1.01x slower                                                 |
| typing_runtime_protocols | 146 us                                                 | 147 us: 1.01x slower                                                  |
| pickle_dict              | 31.6 us                                                | 31.9 us: 1.01x slower                                                 |
| mdp                      | 2.57 sec                                               | 2.59 sec: 1.01x slower                                                |
| scimark_fft              | 358 ms                                                 | 363 ms: 1.01x slower                                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.18 us: 1.01x slower                                                 |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                  |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                  |
| unpack_sequence          | 44.8 ns                                                | 45.5 ns: 1.01x slower                                                 |
| fannkuch                 | 387 ms                                                 | 394 ms: 1.02x slower                                                  |
| pyflate                  | 450 ms                                                 | 458 ms: 1.02x slower                                                  |
| comprehensions           | 20.4 us                                                | 20.9 us: 1.02x slower                                                 |
| json                     | 4.77 ms                                                | 4.89 ms: 1.03x slower                                                 |
| pycparser                | 1.15 sec                                               | 1.18 sec: 1.03x slower                                                |
| pickle                   | 10.6 us                                                | 10.9 us: 1.03x slower                                                 |
| async_generators         | 440 ms                                                 | 453 ms: 1.03x slower                                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.88 ms: 1.03x slower                                                 |
| spectral_norm            | 106 ms                                                 | 110 ms: 1.04x slower                                                  |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.04x slower                                                |
| go                       | 136 ms                                                 | 141 ms: 1.04x slower                                                  |
| mako                     | 10.7 ms                                                | 11.2 ms: 1.04x slower                                                 |
| regex_dna                | 209 ms                                                 | 219 ms: 1.05x slower                                                  |
| regex_effbot             | 3.55 ms                                                | 3.76 ms: 1.06x slower                                                 |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                                  |
| nbody                    | 88.8 ms                                                | 96.1 ms: 1.08x slower                                                 |
| richards                 | 43.2 ms                                                | 46.7 ms: 1.08x slower                                                 |
| richards_super           | 49.0 ms                                                | 53.7 ms: 1.10x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 4.25 ms: 1.11x slower                                                 |
| regex_v8                 | 22.3 ms                                                | 25.9 ms: 1.16x slower                                                 |
| telco                    | 6.87 ms                                                | 8.15 ms: 1.19x slower                                                 |
| dask                     | 365 ms                                                 | 526 ms: 1.44x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                          |

Benchmark hidden because not significant (8): async_tree_memoization, scimark_sor, unpickle_pure_python, hexiom, bench_mp_pool, deepcopy_memo, json_loads, coroutines
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 59.77% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
