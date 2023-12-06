
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 4fa500d
- commit date: 2023-08-13
- overall geometric mean: 1.03x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.39 sec: 1.13x faster                                                    |
| tornado_http   | 99.6 ms                                                | 93.4 ms: 1.07x faster                                                     |
| Geometric mean | (ref)                                                  | 1.10x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 76.0 ms: 1.06x faster                                                     |
| pidigits       | 187 ms                                                 | 201 ms: 1.08x slower                                                      |
| Geometric mean | (ref)                                                  | 1.00x slower                                                              |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| regex_effbot   | 3.55 ms                                                | 3.69 ms: 1.04x slower                                                     |
| regex_dna      | 209 ms                                                 | 225 ms: 1.08x slower                                                      |
| regex_v8       | 22.3 ms                                                | 26.5 ms: 1.19x slower                                                     |
| Geometric mean | (ref)                                                  | 1.06x slower                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.10 sec: 1.05x faster                                                    |
| xml_etree_iterparse  | 104 ms                                                 | 98.6 ms: 1.05x faster                                                     |
| unpickle             | 15.0 us                                                | 14.3 us: 1.05x faster                                                     |
| pickle_pure_python   | 309 us                                                 | 298 us: 1.04x faster                                                      |
| xml_etree_generate   | 84.8 ms                                                | 81.9 ms: 1.04x faster                                                     |
| pickle               | 10.6 us                                                | 10.3 us: 1.03x faster                                                     |
| xml_etree_process    | 58.6 ms                                                | 56.8 ms: 1.03x faster                                                     |
| unpickle_pure_python | 218 us                                                 | 212 us: 1.03x faster                                                      |
| xml_etree_parse      | 154 ms                                                 | 151 ms: 1.02x faster                                                      |
| pickle_list          | 4.62 us                                                | 4.56 us: 1.01x faster                                                     |
| pickle_dict          | 31.6 us                                                | 31.4 us: 1.01x faster                                                     |
| unpickle_list        | 4.95 us                                                | 5.15 us: 1.04x slower                                                     |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                              |

Benchmark hidden because not significant (2): json_dumps, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.20 ms: 1.03x faster                                                     |
| python_startup_no_site | 6.90 ms                                                | 6.72 ms: 1.03x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.03x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                     |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io            | 1.16 sec                                               | 608 ms: 1.90x faster                                                      |
| async_tree_none          | 469 ms                                                 | 313 ms: 1.50x faster                                                      |
| async_tree_memoization   | 573 ms                                                 | 383 ms: 1.50x faster                                                      |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 531 ms: 1.35x faster                                                      |
| docutils                 | 2.70 sec                                               | 2.39 sec: 1.13x faster                                                    |
| crypto_pyaes             | 77.2 ms                                                | 69.2 ms: 1.12x faster                                                     |
| asyncio_tcp              | 526 ms                                                 | 475 ms: 1.11x faster                                                      |
| coverage                 | 94.2 ms                                                | 86.5 ms: 1.09x faster                                                     |
| scimark_monte_carlo      | 71.0 ms                                                | 65.5 ms: 1.08x faster                                                     |
| deltablue                | 3.52 ms                                                | 3.26 ms: 1.08x faster                                                     |
| raytrace                 | 294 ms                                                 | 273 ms: 1.08x faster                                                      |
| logging_format           | 6.90 us                                                | 6.46 us: 1.07x faster                                                     |
| tornado_http             | 99.6 ms                                                | 93.4 ms: 1.07x faster                                                     |
| chaos                    | 63.5 ms                                                | 59.7 ms: 1.06x faster                                                     |
| float                    | 80.7 ms                                                | 76.0 ms: 1.06x faster                                                     |
| logging_simple           | 6.18 us                                                | 5.84 us: 1.06x faster                                                     |
| regex_compile            | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| tomli_loads              | 2.22 sec                                               | 2.10 sec: 1.05x faster                                                    |
| create_gc_cycles         | 1.52 ms                                                | 1.44 ms: 1.05x faster                                                     |
| generators               | 31.1 ms                                                | 29.5 ms: 1.05x faster                                                     |
| xml_etree_iterparse      | 104 ms                                                 | 98.6 ms: 1.05x faster                                                     |
| gc_traversal             | 3.84 ms                                                | 3.66 ms: 1.05x faster                                                     |
| sqlglot_parse            | 1.32 ms                                                | 1.26 ms: 1.05x faster                                                     |
| unpickle                 | 15.0 us                                                | 14.3 us: 1.05x faster                                                     |
| pickle_pure_python       | 309 us                                                 | 298 us: 1.04x faster                                                      |
| sqlglot_transpile        | 1.64 ms                                                | 1.58 ms: 1.04x faster                                                     |
| xml_etree_generate       | 84.8 ms                                                | 81.9 ms: 1.04x faster                                                     |
| pickle                   | 10.6 us                                                | 10.3 us: 1.03x faster                                                     |
| xml_etree_process        | 58.6 ms                                                | 56.8 ms: 1.03x faster                                                     |
| python_startup           | 9.47 ms                                                | 9.20 ms: 1.03x faster                                                     |
| scimark_sor              | 125 ms                                                 | 121 ms: 1.03x faster                                                      |
| unpickle_pure_python     | 218 us                                                 | 212 us: 1.03x faster                                                      |
| python_startup_no_site   | 6.90 ms                                                | 6.72 ms: 1.03x faster                                                     |
| async_generators         | 440 ms                                                 | 429 ms: 1.03x faster                                                      |
| dulwich_log              | 67.9 ms                                                | 66.2 ms: 1.03x faster                                                     |
| hexiom                   | 6.12 ms                                                | 5.98 ms: 1.02x faster                                                     |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                                      |
| typing_runtime_protocols | 146 us                                                 | 143 us: 1.02x faster                                                      |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                                      |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.02x faster                                                      |
| mdp                      | 2.57 sec                                               | 2.52 sec: 1.02x faster                                                    |
| scimark_fft              | 358 ms                                                 | 353 ms: 1.02x faster                                                      |
| bench_thread_pool        | 827 us                                                 | 814 us: 1.02x faster                                                      |
| pickle_list              | 4.62 us                                                | 4.56 us: 1.01x faster                                                     |
| sqlglot_optimize         | 53.3 ms                                                | 52.7 ms: 1.01x faster                                                     |
| pprint_safe_repr         | 735 ms                                                 | 727 ms: 1.01x faster                                                      |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                                     |
| spectral_norm            | 106 ms                                                 | 105 ms: 1.01x faster                                                      |
| pickle_dict              | 31.6 us                                                | 31.4 us: 1.01x faster                                                     |
| nqueens                  | 81.1 ms                                                | 80.7 ms: 1.00x faster                                                     |
| pyflate                  | 450 ms                                                 | 448 ms: 1.00x faster                                                      |
| pprint_pformat           | 1.50 sec                                               | 1.49 sec: 1.00x faster                                                    |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                    |
| comprehensions           | 20.4 us                                                | 20.5 us: 1.00x slower                                                     |
| deepcopy_memo            | 37.4 us                                                | 37.6 us: 1.00x slower                                                     |
| deepcopy_reduce          | 3.14 us                                                | 3.16 us: 1.01x slower                                                     |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                     |
| mypy2                    | 344 ms                                                 | 347 ms: 1.01x slower                                                      |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                      |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.83 ms: 1.02x slower                                                     |
| fannkuch                 | 387 ms                                                 | 394 ms: 1.02x slower                                                      |
| unpack_sequence          | 44.8 ns                                                | 46.1 ns: 1.03x slower                                                     |
| go                       | 136 ms                                                 | 141 ms: 1.04x slower                                                      |
| regex_effbot             | 3.55 ms                                                | 3.69 ms: 1.04x slower                                                     |
| unpickle_list            | 4.95 us                                                | 5.15 us: 1.04x slower                                                     |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                                      |
| pidigits                 | 187 ms                                                 | 201 ms: 1.08x slower                                                      |
| regex_dna                | 209 ms                                                 | 225 ms: 1.08x slower                                                      |
| richards_super           | 49.0 ms                                                | 53.3 ms: 1.09x slower                                                     |
| richards                 | 43.2 ms                                                | 47.4 ms: 1.10x slower                                                     |
| telco                    | 6.87 ms                                                | 8.09 ms: 1.18x slower                                                     |
| regex_v8                 | 22.3 ms                                                | 26.5 ms: 1.19x slower                                                     |
| dask                     | 365 ms                                                 | 501 ms: 1.37x slower                                                      |
| Geometric mean           | (ref)                                                  | 1.03x faster                                                              |

Benchmark hidden because not significant (9): deepcopy, json_dumps, json_loads, coroutines, pathlib, bench_mp_pool, pycparser, nbody, json
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
