
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 97f762a
- commit date: 2023-08-12
- overall geometric mean: 1.03x faster
- HPT reliability: 99.97%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-97f762a |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.44 sec: 1.11x faster                                                    |
| tornado_http   | 99.6 ms                                                | 92.7 ms: 1.07x faster                                                     |
| Geometric mean | (ref)                                                  | 1.09x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-97f762a |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 77.8 ms: 1.04x faster                                                     |
| nbody          | 88.8 ms                                                | 89.6 ms: 1.01x slower                                                     |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| Geometric mean | (ref)                                                  | 1.01x faster                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-97f762a |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| regex_v8       | 22.3 ms                                                | 21.8 ms: 1.03x faster                                                     |
| regex_dna      | 209 ms                                                 | 207 ms: 1.01x faster                                                      |
| regex_effbot   | 3.55 ms                                                | 3.53 ms: 1.00x faster                                                     |
| Geometric mean | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-97f762a |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 294 us: 1.05x faster                                                      |
| unpickle_pure_python | 218 us                                                 | 214 us: 1.02x faster                                                      |
| xml_etree_generate   | 84.8 ms                                                | 83.2 ms: 1.02x faster                                                     |
| pickle_dict          | 31.6 us                                                | 31.1 us: 1.02x faster                                                     |
| xml_etree_process    | 58.6 ms                                                | 57.6 ms: 1.02x faster                                                     |
| unpickle             | 15.0 us                                                | 14.8 us: 1.01x faster                                                     |
| pickle               | 10.6 us                                                | 10.6 us: 1.00x faster                                                     |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                      |
| json_loads           | 25.2 us                                                | 25.5 us: 1.01x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.30 sec: 1.04x slower                                                    |
| xml_etree_parse      | 154 ms                                                 | 166 ms: 1.08x slower                                                      |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                              |

Benchmark hidden because not significant (3): json_dumps, pickle_list, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-97f762a |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.75 ms: 1.02x faster                                                     |
| python_startup         | 9.47 ms                                                | 9.27 ms: 1.02x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-97f762a |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.01x slower                                                     |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-97f762a |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io            | 1.16 sec                                               | 730 ms: 1.58x faster                                                      |
| async_tree_memoization   | 573 ms                                                 | 406 ms: 1.41x faster                                                      |
| async_tree_none          | 469 ms                                                 | 342 ms: 1.37x faster                                                      |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 577 ms: 1.24x faster                                                      |
| crypto_pyaes             | 77.2 ms                                                | 68.3 ms: 1.13x faster                                                     |
| deltablue                | 3.52 ms                                                | 3.13 ms: 1.12x faster                                                     |
| docutils                 | 2.70 sec                                               | 2.44 sec: 1.11x faster                                                    |
| raytrace                 | 294 ms                                                 | 271 ms: 1.08x faster                                                      |
| chaos                    | 63.5 ms                                                | 58.7 ms: 1.08x faster                                                     |
| asyncio_tcp              | 526 ms                                                 | 486 ms: 1.08x faster                                                      |
| tornado_http             | 99.6 ms                                                | 92.7 ms: 1.07x faster                                                     |
| logging_format           | 6.90 us                                                | 6.47 us: 1.07x faster                                                     |
| gc_traversal             | 3.84 ms                                                | 3.61 ms: 1.07x faster                                                     |
| scimark_monte_carlo      | 71.0 ms                                                | 66.9 ms: 1.06x faster                                                     |
| pickle_pure_python       | 309 us                                                 | 294 us: 1.05x faster                                                      |
| scimark_sor              | 125 ms                                                 | 118 ms: 1.05x faster                                                      |
| create_gc_cycles         | 1.52 ms                                                | 1.45 ms: 1.05x faster                                                     |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| unpack_sequence          | 44.8 ns                                                | 42.7 ns: 1.05x faster                                                     |
| logging_simple           | 6.18 us                                                | 5.91 us: 1.05x faster                                                     |
| float                    | 80.7 ms                                                | 77.8 ms: 1.04x faster                                                     |
| sqlglot_transpile        | 1.64 ms                                                | 1.59 ms: 1.03x faster                                                     |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                                     |
| dulwich_log              | 67.9 ms                                                | 66.0 ms: 1.03x faster                                                     |
| scimark_lu               | 114 ms                                                 | 111 ms: 1.03x faster                                                      |
| regex_v8                 | 22.3 ms                                                | 21.8 ms: 1.03x faster                                                     |
| pprint_safe_repr         | 735 ms                                                 | 717 ms: 1.03x faster                                                      |
| pprint_pformat           | 1.50 sec                                               | 1.47 sec: 1.02x faster                                                    |
| unpickle_pure_python     | 218 us                                                 | 214 us: 1.02x faster                                                      |
| python_startup_no_site   | 6.90 ms                                                | 6.75 ms: 1.02x faster                                                     |
| pyflate                  | 450 ms                                                 | 441 ms: 1.02x faster                                                      |
| python_startup           | 9.47 ms                                                | 9.27 ms: 1.02x faster                                                     |
| xml_etree_generate       | 84.8 ms                                                | 83.2 ms: 1.02x faster                                                     |
| pickle_dict              | 31.6 us                                                | 31.1 us: 1.02x faster                                                     |
| xml_etree_process        | 58.6 ms                                                | 57.6 ms: 1.02x faster                                                     |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                                     |
| mdp                      | 2.57 sec                                               | 2.53 sec: 1.01x faster                                                    |
| coverage                 | 94.2 ms                                                | 92.8 ms: 1.01x faster                                                     |
| unpickle                 | 15.0 us                                                | 14.8 us: 1.01x faster                                                     |
| scimark_fft              | 358 ms                                                 | 354 ms: 1.01x faster                                                      |
| async_generators         | 440 ms                                                 | 434 ms: 1.01x faster                                                      |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                      |
| hexiom                   | 6.12 ms                                                | 6.05 ms: 1.01x faster                                                     |
| comprehensions           | 20.4 us                                                | 20.2 us: 1.01x faster                                                     |
| regex_dna                | 209 ms                                                 | 207 ms: 1.01x faster                                                      |
| deepcopy                 | 355 us                                                 | 354 us: 1.01x faster                                                      |
| regex_effbot             | 3.55 ms                                                | 3.53 ms: 1.00x faster                                                     |
| pickle                   | 10.6 us                                                | 10.6 us: 1.00x faster                                                     |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                    |
| deepcopy_memo            | 37.4 us                                                | 37.5 us: 1.00x slower                                                     |
| meteor_contest           | 105 ms                                                 | 105 ms: 1.00x slower                                                      |
| typing_runtime_protocols | 146 us                                                 | 147 us: 1.01x slower                                                      |
| nbody                    | 88.8 ms                                                | 89.6 ms: 1.01x slower                                                     |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                     |
| sqlite_synth             | 2.76 us                                                | 2.78 us: 1.01x slower                                                     |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                      |
| json_loads               | 25.2 us                                                | 25.5 us: 1.01x slower                                                     |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.01x slower                                                     |
| fannkuch                 | 387 ms                                                 | 392 ms: 1.01x slower                                                      |
| json                     | 4.77 ms                                                | 4.87 ms: 1.02x slower                                                     |
| go                       | 136 ms                                                 | 139 ms: 1.03x slower                                                      |
| pycparser                | 1.15 sec                                               | 1.18 sec: 1.03x slower                                                    |
| tomli_loads              | 2.22 sec                                               | 2.30 sec: 1.04x slower                                                    |
| mypy2                    | 344 ms                                                 | 359 ms: 1.05x slower                                                      |
| richards                 | 43.2 ms                                                | 46.2 ms: 1.07x slower                                                     |
| richards_super           | 49.0 ms                                                | 52.8 ms: 1.08x slower                                                     |
| xml_etree_parse          | 154 ms                                                 | 166 ms: 1.08x slower                                                      |
| telco                    | 6.87 ms                                                | 7.98 ms: 1.16x slower                                                     |
| dask                     | 365 ms                                                 | 495 ms: 1.36x slower                                                      |
| Geometric mean           | (ref)                                                  | 1.03x faster                                                              |

Benchmark hidden because not significant (12): generators, json_dumps, scimark_sparse_mat_mult, bench_thread_pool, spectral_norm, bench_mp_pool, sqlglot_optimize, deepcopy_reduce, pickle_list, unpickle_list, nqueens, logging_silent
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.97% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
