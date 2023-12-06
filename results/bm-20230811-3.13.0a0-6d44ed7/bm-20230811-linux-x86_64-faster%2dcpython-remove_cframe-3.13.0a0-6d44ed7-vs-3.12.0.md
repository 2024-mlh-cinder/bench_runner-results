
# Results vs. 3.12.0

- fork: faster-cpython
- ref: remove_cframe
- machine: linux-x86_64
- commit hash: 6d44ed7
- commit date: 2023-08-11
- overall geometric mean: 1.00x faster
- HPT reliability: 99.91%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-remove_cframe-3.13.0a0-6d44ed7 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.63 sec: 1.03x faster                                                   |
| tornado_http   | 99.6 ms                                                | 95.2 ms: 1.05x faster                                                    |
| Geometric mean | (ref)                                                  | 1.04x faster                                                             |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-remove_cframe-3.13.0a0-6d44ed7 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.6 ms: 1.01x faster                                                    |
| nbody          | 88.8 ms                                                | 89.8 ms: 1.01x slower                                                    |
| pidigits       | 187 ms                                                 | 201 ms: 1.07x slower                                                     |
| Geometric mean | (ref)                                                  | 1.02x slower                                                             |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-remove_cframe-3.13.0a0-6d44ed7 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                     |
| regex_v8       | 22.3 ms                                                | 23.1 ms: 1.03x slower                                                    |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                                     |
| regex_effbot   | 3.55 ms                                                | 3.79 ms: 1.07x slower                                                    |
| Geometric mean | (ref)                                                  | 1.02x slower                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-remove_cframe-3.13.0a0-6d44ed7 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.0 us: 1.07x faster                                                    |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                   |
| pickle_pure_python   | 309 us                                                 | 300 us: 1.03x faster                                                     |
| xml_etree_generate   | 84.8 ms                                                | 83.0 ms: 1.02x faster                                                    |
| unpickle_pure_python | 218 us                                                 | 214 us: 1.02x faster                                                     |
| xml_etree_process    | 58.6 ms                                                | 57.6 ms: 1.02x faster                                                    |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                     |
| pickle_dict          | 31.6 us                                                | 31.3 us: 1.01x faster                                                    |
| json_dumps           | 9.85 ms                                                | 9.75 ms: 1.01x faster                                                    |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                     |
| unpickle_list        | 4.95 us                                                | 4.92 us: 1.01x faster                                                    |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                             |

Benchmark hidden because not significant (3): pickle_list, json_loads, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-remove_cframe-3.13.0a0-6d44ed7 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.33 ms: 1.02x faster                                                    |
| python_startup_no_site | 6.90 ms                                                | 6.82 ms: 1.01x faster                                                    |
| Geometric mean         | (ref)                                                  | 1.01x faster                                                             |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-remove_cframe-3.13.0a0-6d44ed7 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 67.7 ms: 1.14x faster                                                    |
| coverage                 | 94.2 ms                                                | 84.9 ms: 1.11x faster                                                    |
| raytrace                 | 294 ms                                                 | 271 ms: 1.08x faster                                                     |
| asyncio_tcp              | 526 ms                                                 | 485 ms: 1.08x faster                                                     |
| async_tree_none          | 469 ms                                                 | 436 ms: 1.08x faster                                                     |
| logging_format           | 6.90 us                                                | 6.42 us: 1.08x faster                                                    |
| generators               | 31.1 ms                                                | 28.9 ms: 1.07x faster                                                    |
| unpack_sequence          | 44.8 ns                                                | 41.8 ns: 1.07x faster                                                    |
| unpickle                 | 15.0 us                                                | 14.0 us: 1.07x faster                                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 66.5 ms: 1.07x faster                                                    |
| deltablue                | 3.52 ms                                                | 3.30 ms: 1.07x faster                                                    |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                     |
| chaos                    | 63.5 ms                                                | 60.5 ms: 1.05x faster                                                    |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                   |
| sqlglot_parse            | 1.32 ms                                                | 1.26 ms: 1.05x faster                                                    |
| tornado_http             | 99.6 ms                                                | 95.2 ms: 1.05x faster                                                    |
| logging_simple           | 6.18 us                                                | 5.91 us: 1.05x faster                                                    |
| sqlglot_transpile        | 1.64 ms                                                | 1.58 ms: 1.04x faster                                                    |
| create_gc_cycles         | 1.52 ms                                                | 1.47 ms: 1.03x faster                                                    |
| pickle_pure_python       | 309 us                                                 | 300 us: 1.03x faster                                                     |
| dulwich_log              | 67.9 ms                                                | 65.9 ms: 1.03x faster                                                    |
| pprint_safe_repr         | 735 ms                                                 | 714 ms: 1.03x faster                                                     |
| docutils                 | 2.70 sec                                               | 2.63 sec: 1.03x faster                                                   |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 696 ms: 1.03x faster                                                     |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                                     |
| xml_etree_generate       | 84.8 ms                                                | 83.0 ms: 1.02x faster                                                    |
| async_tree_memoization   | 573 ms                                                 | 561 ms: 1.02x faster                                                     |
| unpickle_pure_python     | 218 us                                                 | 214 us: 1.02x faster                                                     |
| pprint_pformat           | 1.50 sec                                               | 1.47 sec: 1.02x faster                                                   |
| xml_etree_process        | 58.6 ms                                                | 57.6 ms: 1.02x faster                                                    |
| python_startup           | 9.47 ms                                                | 9.33 ms: 1.02x faster                                                    |
| float                    | 80.7 ms                                                | 79.6 ms: 1.01x faster                                                    |
| bench_thread_pool        | 827 us                                                 | 815 us: 1.01x faster                                                     |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                     |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                                     |
| hexiom                   | 6.12 ms                                                | 6.04 ms: 1.01x faster                                                    |
| sqlglot_optimize         | 53.3 ms                                                | 52.6 ms: 1.01x faster                                                    |
| scimark_fft              | 358 ms                                                 | 354 ms: 1.01x faster                                                     |
| deepcopy                 | 355 us                                                 | 351 us: 1.01x faster                                                     |
| coroutines               | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                    |
| python_startup_no_site   | 6.90 ms                                                | 6.82 ms: 1.01x faster                                                    |
| pickle_dict              | 31.6 us                                                | 31.3 us: 1.01x faster                                                    |
| json_dumps               | 9.85 ms                                                | 9.75 ms: 1.01x faster                                                    |
| fannkuch                 | 387 ms                                                 | 384 ms: 1.01x faster                                                     |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                     |
| deepcopy_memo            | 37.4 us                                                | 37.1 us: 1.01x faster                                                    |
| pyflate                  | 450 ms                                                 | 447 ms: 1.01x faster                                                     |
| spectral_norm            | 106 ms                                                 | 105 ms: 1.01x faster                                                     |
| unpickle_list            | 4.95 us                                                | 4.92 us: 1.01x faster                                                    |
| mdp                      | 2.57 sec                                               | 2.56 sec: 1.00x faster                                                   |
| nqueens                  | 81.1 ms                                                | 81.6 ms: 1.01x slower                                                    |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                     |
| nbody                    | 88.8 ms                                                | 89.8 ms: 1.01x slower                                                    |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                                    |
| typing_runtime_protocols | 146 us                                                 | 148 us: 1.01x slower                                                     |
| comprehensions           | 20.4 us                                                | 20.7 us: 1.01x slower                                                    |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.02x slower                                                   |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.88 ms: 1.03x slower                                                    |
| regex_v8                 | 22.3 ms                                                | 23.1 ms: 1.03x slower                                                    |
| regex_dna                | 209 ms                                                 | 215 ms: 1.03x slower                                                     |
| go                       | 136 ms                                                 | 140 ms: 1.03x slower                                                     |
| async_generators         | 440 ms                                                 | 457 ms: 1.04x slower                                                     |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                                     |
| regex_effbot             | 3.55 ms                                                | 3.79 ms: 1.07x slower                                                    |
| pidigits                 | 187 ms                                                 | 201 ms: 1.07x slower                                                     |
| gc_traversal             | 3.84 ms                                                | 4.18 ms: 1.09x slower                                                    |
| richards_super           | 49.0 ms                                                | 54.3 ms: 1.11x slower                                                    |
| richards                 | 43.2 ms                                                | 48.0 ms: 1.11x slower                                                    |
| telco                    | 6.87 ms                                                | 7.94 ms: 1.16x slower                                                    |
| mypy2                    | 344 ms                                                 | 456 ms: 1.33x slower                                                     |
| dask                     | 365 ms                                                 | 516 ms: 1.42x slower                                                     |
| Geometric mean           | (ref)                                                  | 1.00x faster                                                             |

Benchmark hidden because not significant (11): pickle_list, asyncio_tcp_ssl, sqlite_synth, bench_mp_pool, mako, scimark_lu, json_loads, pathlib, pycparser, json, pickle
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.91% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
