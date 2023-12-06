
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 482fad7
- commit date: 2023-08-26
- overall geometric mean: 1.00x slower
- HPT reliability: 91.76%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-linux-x86_64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.64 sec: 1.02x faster                                |
| tornado_http   | 99.6 ms                                                | 95.6 ms: 1.04x faster                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-linux-x86_64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 80.7 ms                                                | 79.9 ms: 1.01x faster                                 |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                  |
| nbody          | 88.8 ms                                                | 93.0 ms: 1.05x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-linux-x86_64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                  |
| regex_dna      | 209 ms                                                 | 228 ms: 1.09x slower                                  |
| regex_effbot   | 3.55 ms                                                | 3.88 ms: 1.09x slower                                 |
| regex_v8       | 22.3 ms                                                | 25.5 ms: 1.14x slower                                 |
| Geometric mean | (ref)                                                  | 1.07x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-linux-x86_64-python-main-3.13.0a0-482fad7 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.5 us: 1.04x faster                                 |
| tomli_loads          | 2.22 sec                                               | 2.14 sec: 1.03x faster                                |
| pickle_list          | 4.62 us                                                | 4.52 us: 1.02x faster                                 |
| unpickle_pure_python | 218 us                                                 | 215 us: 1.02x faster                                  |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                  |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                 |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                  |
| pickle_pure_python   | 309 us                                                 | 306 us: 1.01x faster                                  |
| xml_etree_process    | 58.6 ms                                                | 58.0 ms: 1.01x faster                                 |
| xml_etree_generate   | 84.8 ms                                                | 84.0 ms: 1.01x faster                                 |
| json_loads           | 25.2 us                                                | 25.4 us: 1.01x slower                                 |
| json_dumps           | 9.85 ms                                                | 9.95 ms: 1.01x slower                                 |
| pickle_dict          | 31.6 us                                                | 32.2 us: 1.02x slower                                 |
| unpickle_list        | 4.95 us                                                | 5.15 us: 1.04x slower                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-linux-x86_64-python-main-3.13.0a0-482fad7 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.39 ms: 1.01x faster                                 |
| python_startup_no_site | 6.90 ms                                                | 6.87 ms: 1.00x faster                                 |
| Geometric mean         | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-linux-x86_64-python-main-3.13.0a0-482fad7 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230826-linux-x86_64-python-main-3.13.0a0-482fad7 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 69.2 ms: 1.12x faster                                 |
| coverage                 | 94.2 ms                                                | 85.0 ms: 1.11x faster                                 |
| asyncio_tcp              | 526 ms                                                 | 477 ms: 1.10x faster                                  |
| generators               | 31.1 ms                                                | 28.9 ms: 1.07x faster                                 |
| logging_format           | 6.90 us                                                | 6.45 us: 1.07x faster                                 |
| async_tree_none          | 469 ms                                                 | 440 ms: 1.07x faster                                  |
| scimark_monte_carlo      | 71.0 ms                                                | 66.8 ms: 1.06x faster                                 |
| deltablue                | 3.52 ms                                                | 3.31 ms: 1.06x faster                                 |
| raytrace                 | 294 ms                                                 | 279 ms: 1.06x faster                                  |
| chaos                    | 63.5 ms                                                | 60.5 ms: 1.05x faster                                 |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                  |
| scimark_fft              | 358 ms                                                 | 343 ms: 1.04x faster                                  |
| scimark_lu               | 114 ms                                                 | 109 ms: 1.04x faster                                  |
| tornado_http             | 99.6 ms                                                | 95.6 ms: 1.04x faster                                 |
| logging_simple           | 6.18 us                                                | 5.96 us: 1.04x faster                                 |
| unpickle                 | 15.0 us                                                | 14.5 us: 1.04x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.14 sec: 1.03x faster                                |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                 |
| dulwich_log              | 67.9 ms                                                | 66.2 ms: 1.03x faster                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.02x faster                                 |
| docutils                 | 2.70 sec                                               | 2.64 sec: 1.02x faster                                |
| pickle_list              | 4.62 us                                                | 4.52 us: 1.02x faster                                 |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                  |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 701 ms: 1.02x faster                                  |
| typing_runtime_protocols | 146 us                                                 | 144 us: 1.02x faster                                  |
| sqlite_synth             | 2.76 us                                                | 2.72 us: 1.02x faster                                 |
| unpickle_pure_python     | 218 us                                                 | 215 us: 1.02x faster                                  |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                  |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                 |
| mypy2                    | 344 ms                                                 | 339 ms: 1.01x faster                                  |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                 |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                  |
| float                    | 80.7 ms                                                | 79.9 ms: 1.01x faster                                 |
| async_tree_memoization   | 573 ms                                                 | 567 ms: 1.01x faster                                  |
| pickle_pure_python       | 309 us                                                 | 306 us: 1.01x faster                                  |
| xml_etree_process        | 58.6 ms                                                | 58.0 ms: 1.01x faster                                 |
| xml_etree_generate       | 84.8 ms                                                | 84.0 ms: 1.01x faster                                 |
| python_startup           | 9.47 ms                                                | 9.39 ms: 1.01x faster                                 |
| bench_thread_pool        | 827 us                                                 | 820 us: 1.01x faster                                  |
| nqueens                  | 81.1 ms                                                | 80.6 ms: 1.01x faster                                 |
| sqlglot_optimize         | 53.3 ms                                                | 52.9 ms: 1.01x faster                                 |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.87 ms: 1.00x faster                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                |
| json_loads               | 25.2 us                                                | 25.4 us: 1.01x slower                                 |
| pathlib                  | 18.5 ms                                                | 18.6 ms: 1.01x slower                                 |
| json_dumps               | 9.85 ms                                                | 9.95 ms: 1.01x slower                                 |
| hexiom                   | 6.12 ms                                                | 6.19 ms: 1.01x slower                                 |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.80 ms: 1.01x slower                                 |
| deepcopy_memo            | 37.4 us                                                | 37.9 us: 1.01x slower                                 |
| spectral_norm            | 106 ms                                                 | 108 ms: 1.01x slower                                  |
| pickle_dict              | 31.6 us                                                | 32.2 us: 1.02x slower                                 |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.02x slower                                 |
| meteor_contest           | 105 ms                                                 | 107 ms: 1.02x slower                                  |
| fannkuch                 | 387 ms                                                 | 396 ms: 1.02x slower                                  |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                |
| json                     | 4.77 ms                                                | 4.91 ms: 1.03x slower                                 |
| comprehensions           | 20.4 us                                                | 21.1 us: 1.03x slower                                 |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.04x slower                                  |
| unpickle_list            | 4.95 us                                                | 5.15 us: 1.04x slower                                 |
| async_generators         | 440 ms                                                 | 459 ms: 1.04x slower                                  |
| nbody                    | 88.8 ms                                                | 93.0 ms: 1.05x slower                                 |
| pycparser                | 1.15 sec                                               | 1.21 sec: 1.05x slower                                |
| go                       | 136 ms                                                 | 143 ms: 1.05x slower                                  |
| unpack_sequence          | 44.8 ns                                                | 48.1 ns: 1.07x slower                                 |
| regex_dna                | 209 ms                                                 | 228 ms: 1.09x slower                                  |
| regex_effbot             | 3.55 ms                                                | 3.88 ms: 1.09x slower                                 |
| richards_super           | 49.0 ms                                                | 53.9 ms: 1.10x slower                                 |
| richards                 | 43.2 ms                                                | 48.3 ms: 1.12x slower                                 |
| regex_v8                 | 22.3 ms                                                | 25.5 ms: 1.14x slower                                 |
| telco                    | 6.87 ms                                                | 8.04 ms: 1.17x slower                                 |
| dask                     | 365 ms                                                 | 524 ms: 1.44x slower                                  |
| Geometric mean           | (ref)                                                  | 1.00x slower                                          |

Benchmark hidden because not significant (8): mdp, deepcopy, deepcopy_reduce, pprint_pformat, bench_mp_pool, pyflate, pprint_safe_repr, coroutines
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 91.76% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
