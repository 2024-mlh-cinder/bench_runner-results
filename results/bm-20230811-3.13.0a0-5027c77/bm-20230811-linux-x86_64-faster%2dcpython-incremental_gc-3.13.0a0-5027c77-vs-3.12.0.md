
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 5027c77
- commit date: 2023-08-11
- overall geometric mean: 1.04x faster
- HPT reliability: 99.86%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-5027c77 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.38 sec: 1.14x faster                                                    |
| tornado_http   | 99.6 ms                                                | 94.1 ms: 1.06x faster                                                     |
| Geometric mean | (ref)                                                  | 1.10x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-5027c77 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 72.7 ms: 1.11x faster                                                     |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| nbody          | 88.8 ms                                                | 92.9 ms: 1.05x slower                                                     |
| Geometric mean | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-5027c77 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| regex_v8       | 22.3 ms                                                | 22.4 ms: 1.00x slower                                                     |
| regex_effbot   | 3.55 ms                                                | 3.66 ms: 1.03x slower                                                     |
| Geometric mean | (ref)                                                  | 1.00x faster                                                              |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-5027c77 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| xml_etree_iterparse  | 104 ms                                                 | 94.0 ms: 1.10x faster                                                     |
| xml_etree_parse      | 154 ms                                                 | 140 ms: 1.10x faster                                                      |
| xml_etree_generate   | 84.8 ms                                                | 80.9 ms: 1.05x faster                                                     |
| xml_etree_process    | 58.6 ms                                                | 56.6 ms: 1.03x faster                                                     |
| pickle_pure_python   | 309 us                                                 | 299 us: 1.03x faster                                                      |
| unpickle_pure_python | 218 us                                                 | 212 us: 1.03x faster                                                      |
| json_dumps           | 9.85 ms                                                | 9.76 ms: 1.01x faster                                                     |
| pickle_dict          | 31.6 us                                                | 31.5 us: 1.00x faster                                                     |
| json_loads           | 25.2 us                                                | 25.4 us: 1.01x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.30 sec: 1.04x slower                                                    |
| unpickle_list        | 4.95 us                                                | 5.13 us: 1.04x slower                                                     |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                              |

Benchmark hidden because not significant (3): pickle, pickle_list, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-5027c77 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.30 ms: 1.02x faster                                                     |
| python_startup_no_site | 6.90 ms                                                | 6.79 ms: 1.02x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-5027c77 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io            | 1.16 sec                                               | 562 ms: 2.06x faster                                                      |
| async_tree_none          | 469 ms                                                 | 274 ms: 1.72x faster                                                      |
| async_tree_memoization   | 573 ms                                                 | 337 ms: 1.70x faster                                                      |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 498 ms: 1.44x faster                                                      |
| deltablue                | 3.52 ms                                                | 3.08 ms: 1.14x faster                                                     |
| docutils                 | 2.70 sec                                               | 2.38 sec: 1.14x faster                                                    |
| float                    | 80.7 ms                                                | 72.7 ms: 1.11x faster                                                     |
| gc_traversal             | 3.84 ms                                                | 3.46 ms: 1.11x faster                                                     |
| generators               | 31.1 ms                                                | 28.0 ms: 1.11x faster                                                     |
| create_gc_cycles         | 1.52 ms                                                | 1.37 ms: 1.11x faster                                                     |
| raytrace                 | 294 ms                                                 | 266 ms: 1.10x faster                                                      |
| xml_etree_iterparse      | 104 ms                                                 | 94.0 ms: 1.10x faster                                                     |
| xml_etree_parse          | 154 ms                                                 | 140 ms: 1.10x faster                                                      |
| asyncio_tcp              | 526 ms                                                 | 483 ms: 1.09x faster                                                      |
| pycparser                | 1.15 sec                                               | 1.06 sec: 1.08x faster                                                    |
| crypto_pyaes             | 77.2 ms                                                | 71.5 ms: 1.08x faster                                                     |
| chaos                    | 63.5 ms                                                | 58.9 ms: 1.08x faster                                                     |
| logging_format           | 6.90 us                                                | 6.44 us: 1.07x faster                                                     |
| async_generators         | 440 ms                                                 | 416 ms: 1.06x faster                                                      |
| tornado_http             | 99.6 ms                                                | 94.1 ms: 1.06x faster                                                     |
| scimark_monte_carlo      | 71.0 ms                                                | 67.3 ms: 1.06x faster                                                     |
| xml_etree_generate       | 84.8 ms                                                | 80.9 ms: 1.05x faster                                                     |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| logging_simple           | 6.18 us                                                | 5.89 us: 1.05x faster                                                     |
| xml_etree_process        | 58.6 ms                                                | 56.6 ms: 1.03x faster                                                     |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                                     |
| pickle_pure_python       | 309 us                                                 | 299 us: 1.03x faster                                                      |
| unpickle_pure_python     | 218 us                                                 | 212 us: 1.03x faster                                                      |
| dulwich_log              | 67.9 ms                                                | 66.0 ms: 1.03x faster                                                     |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.03x faster                                                     |
| pyflate                  | 450 ms                                                 | 438 ms: 1.03x faster                                                      |
| pprint_safe_repr         | 735 ms                                                 | 716 ms: 1.03x faster                                                      |
| pprint_pformat           | 1.50 sec                                               | 1.47 sec: 1.02x faster                                                    |
| python_startup           | 9.47 ms                                                | 9.30 ms: 1.02x faster                                                     |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                                      |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                                      |
| mypy2                    | 344 ms                                                 | 338 ms: 1.02x faster                                                      |
| python_startup_no_site   | 6.90 ms                                                | 6.79 ms: 1.02x faster                                                     |
| hexiom                   | 6.12 ms                                                | 6.04 ms: 1.01x faster                                                     |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                      |
| typing_runtime_protocols | 146 us                                                 | 144 us: 1.01x faster                                                      |
| comprehensions           | 20.4 us                                                | 20.3 us: 1.01x faster                                                     |
| json_dumps               | 9.85 ms                                                | 9.76 ms: 1.01x faster                                                     |
| sqlglot_optimize         | 53.3 ms                                                | 52.9 ms: 1.01x faster                                                     |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                                                    |
| pickle_dict              | 31.6 us                                                | 31.5 us: 1.00x faster                                                     |
| nqueens                  | 81.1 ms                                                | 81.4 ms: 1.00x slower                                                     |
| regex_v8                 | 22.3 ms                                                | 22.4 ms: 1.00x slower                                                     |
| json_loads               | 25.2 us                                                | 25.4 us: 1.01x slower                                                     |
| scimark_fft              | 358 ms                                                 | 361 ms: 1.01x slower                                                      |
| go                       | 136 ms                                                 | 137 ms: 1.01x slower                                                      |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                      |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                     |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| deepcopy_memo            | 37.4 us                                                | 38.0 us: 1.02x slower                                                     |
| json                     | 4.77 ms                                                | 4.85 ms: 1.02x slower                                                     |
| spectral_norm            | 106 ms                                                 | 108 ms: 1.02x slower                                                      |
| fannkuch                 | 387 ms                                                 | 395 ms: 1.02x slower                                                      |
| deepcopy_reduce          | 3.14 us                                                | 3.21 us: 1.02x slower                                                     |
| regex_effbot             | 3.55 ms                                                | 3.66 ms: 1.03x slower                                                     |
| tomli_loads              | 2.22 sec                                               | 2.30 sec: 1.04x slower                                                    |
| unpickle_list            | 4.95 us                                                | 5.13 us: 1.04x slower                                                     |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.04x slower                                                      |
| nbody                    | 88.8 ms                                                | 92.9 ms: 1.05x slower                                                     |
| mdp                      | 2.57 sec                                               | 2.72 sec: 1.06x slower                                                    |
| richards                 | 43.2 ms                                                | 46.6 ms: 1.08x slower                                                     |
| unpack_sequence          | 44.8 ns                                                | 48.7 ns: 1.09x slower                                                     |
| richards_super           | 49.0 ms                                                | 53.7 ms: 1.10x slower                                                     |
| telco                    | 6.87 ms                                                | 8.00 ms: 1.16x slower                                                     |
| dask                     | 365 ms                                                 | 484 ms: 1.33x slower                                                      |
| Geometric mean           | (ref)                                                  | 1.04x faster                                                              |

Benchmark hidden because not significant (12): sqlite_synth, pickle, pickle_list, deepcopy, unpickle, bench_mp_pool, coverage, bench_thread_pool, mako, coroutines, regex_dna, scimark_sparse_mat_mult
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.86% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
