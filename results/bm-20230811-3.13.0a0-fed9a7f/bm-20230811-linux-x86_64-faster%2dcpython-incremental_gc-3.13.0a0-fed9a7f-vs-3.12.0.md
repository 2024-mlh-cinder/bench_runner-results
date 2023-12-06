
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: fed9a7f
- commit date: 2023-08-11
- overall geometric mean: 1.01x slower
- HPT reliability: 98.73%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-fed9a7f |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.57 sec: 1.05x faster                                                    |
| Geometric mean | (ref)                                                  | 1.02x faster                                                              |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-fed9a7f |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| nbody          | 88.8 ms                                                | 87.7 ms: 1.01x faster                                                     |
| pidigits       | 187 ms                                                 | 201 ms: 1.08x slower                                                      |
| float          | 80.7 ms                                                | 87.7 ms: 1.09x slower                                                     |
| Geometric mean | (ref)                                                  | 1.05x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-fed9a7f |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| regex_effbot   | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                     |
| regex_v8       | 22.3 ms                                                | 22.8 ms: 1.02x slower                                                     |
| Geometric mean | (ref)                                                  | 1.01x faster                                                              |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-fed9a7f |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 293 us: 1.05x faster                                                      |
| unpickle_pure_python | 218 us                                                 | 211 us: 1.03x faster                                                      |
| json_dumps           | 9.85 ms                                                | 9.68 ms: 1.02x faster                                                     |
| pickle_dict          | 31.6 us                                                | 31.6 us: 1.00x faster                                                     |
| unpickle_list        | 4.95 us                                                | 4.99 us: 1.01x slower                                                     |
| xml_etree_process    | 58.6 ms                                                | 60.0 ms: 1.03x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.30 sec: 1.04x slower                                                    |
| xml_etree_generate   | 84.8 ms                                                | 88.1 ms: 1.04x slower                                                     |
| xml_etree_parse      | 154 ms                                                 | 346 ms: 2.25x slower                                                      |
| xml_etree_iterparse  | 104 ms                                                 | 323 ms: 3.11x slower                                                      |
| Geometric mean       | (ref)                                                  | 1.15x slower                                                              |

Benchmark hidden because not significant (4): pickle, unpickle, pickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-fed9a7f |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.92 ms: 1.00x slower                                                     |
| python_startup         | 9.47 ms                                                | 9.52 ms: 1.01x slower                                                     |
| Geometric mean         | (ref)                                                  | 1.00x slower                                                              |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-fed9a7f |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io           | 1.16 sec                                               | 706 ms: 1.64x faster                                                      |
| async_tree_none         | 469 ms                                                 | 327 ms: 1.43x faster                                                      |
| async_tree_memoization  | 573 ms                                                 | 446 ms: 1.28x faster                                                      |
| async_tree_cpu_io_mixed | 714 ms                                                 | 578 ms: 1.24x faster                                                      |
| generators              | 31.1 ms                                                | 28.2 ms: 1.10x faster                                                     |
| crypto_pyaes            | 77.2 ms                                                | 70.4 ms: 1.10x faster                                                     |
| deltablue               | 3.52 ms                                                | 3.21 ms: 1.10x faster                                                     |
| raytrace                | 294 ms                                                 | 269 ms: 1.09x faster                                                      |
| asyncio_tcp             | 526 ms                                                 | 484 ms: 1.09x faster                                                      |
| logging_format          | 6.90 us                                                | 6.43 us: 1.07x faster                                                     |
| chaos                   | 63.5 ms                                                | 59.4 ms: 1.07x faster                                                     |
| pickle_pure_python      | 309 us                                                 | 293 us: 1.05x faster                                                      |
| create_gc_cycles        | 1.52 ms                                                | 1.44 ms: 1.05x faster                                                     |
| regex_compile           | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| docutils                | 2.70 sec                                               | 2.57 sec: 1.05x faster                                                    |
| logging_simple          | 6.18 us                                                | 5.89 us: 1.05x faster                                                     |
| scimark_sor             | 125 ms                                                 | 120 ms: 1.04x faster                                                      |
| pprint_safe_repr        | 735 ms                                                 | 710 ms: 1.03x faster                                                      |
| unpickle_pure_python    | 218 us                                                 | 211 us: 1.03x faster                                                      |
| dulwich_log             | 67.9 ms                                                | 65.9 ms: 1.03x faster                                                     |
| scimark_monte_carlo     | 71.0 ms                                                | 69.1 ms: 1.03x faster                                                     |
| pprint_pformat          | 1.50 sec                                               | 1.46 sec: 1.03x faster                                                    |
| coroutines              | 22.4 ms                                                | 21.9 ms: 1.02x faster                                                     |
| nqueens                 | 81.1 ms                                                | 79.2 ms: 1.02x faster                                                     |
| deepcopy                | 355 us                                                 | 347 us: 1.02x faster                                                      |
| scimark_lu              | 114 ms                                                 | 111 ms: 1.02x faster                                                      |
| sqlglot_normalize       | 107 ms                                                 | 105 ms: 1.02x faster                                                      |
| async_generators        | 440 ms                                                 | 432 ms: 1.02x faster                                                      |
| json_dumps              | 9.85 ms                                                | 9.68 ms: 1.02x faster                                                     |
| hexiom                  | 6.12 ms                                                | 6.03 ms: 1.02x faster                                                     |
| nbody                   | 88.8 ms                                                | 87.7 ms: 1.01x faster                                                     |
| sqlglot_transpile       | 1.64 ms                                                | 1.62 ms: 1.01x faster                                                     |
| coverage                | 94.2 ms                                                | 93.3 ms: 1.01x faster                                                     |
| unpack_sequence         | 44.8 ns                                                | 44.4 ns: 1.01x faster                                                     |
| spectral_norm           | 106 ms                                                 | 105 ms: 1.01x faster                                                      |
| sqlglot_parse           | 1.32 ms                                                | 1.31 ms: 1.01x faster                                                     |
| scimark_fft             | 358 ms                                                 | 356 ms: 1.01x faster                                                      |
| bench_thread_pool       | 827 us                                                 | 822 us: 1.01x faster                                                      |
| sqlglot_optimize        | 53.3 ms                                                | 53.0 ms: 1.01x faster                                                     |
| mdp                     | 2.57 sec                                               | 2.55 sec: 1.01x faster                                                    |
| asyncio_tcp_ssl         | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                    |
| pickle_dict             | 31.6 us                                                | 31.6 us: 1.00x faster                                                     |
| comprehensions          | 20.4 us                                                | 20.5 us: 1.00x slower                                                     |
| python_startup_no_site  | 6.90 ms                                                | 6.92 ms: 1.00x slower                                                     |
| deepcopy_memo           | 37.4 us                                                | 37.6 us: 1.00x slower                                                     |
| fannkuch                | 387 ms                                                 | 389 ms: 1.00x slower                                                      |
| python_startup          | 9.47 ms                                                | 9.52 ms: 1.01x slower                                                     |
| regex_effbot            | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                     |
| pathlib                 | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                     |
| unpickle_list           | 4.95 us                                                | 4.99 us: 1.01x slower                                                     |
| go                      | 136 ms                                                 | 137 ms: 1.01x slower                                                      |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.82 ms: 1.02x slower                                                     |
| regex_v8                | 22.3 ms                                                | 22.8 ms: 1.02x slower                                                     |
| xml_etree_process       | 58.6 ms                                                | 60.0 ms: 1.03x slower                                                     |
| gc_traversal            | 3.84 ms                                                | 3.94 ms: 1.03x slower                                                     |
| logging_silent          | 99.1 ns                                                | 103 ns: 1.04x slower                                                      |
| tomli_loads             | 2.22 sec                                               | 2.30 sec: 1.04x slower                                                    |
| xml_etree_generate      | 84.8 ms                                                | 88.1 ms: 1.04x slower                                                     |
| richards_super          | 49.0 ms                                                | 52.6 ms: 1.07x slower                                                     |
| richards                | 43.2 ms                                                | 46.4 ms: 1.07x slower                                                     |
| pidigits                | 187 ms                                                 | 201 ms: 1.08x slower                                                      |
| float                   | 80.7 ms                                                | 87.7 ms: 1.09x slower                                                     |
| telco                   | 6.87 ms                                                | 7.72 ms: 1.12x slower                                                     |
| mypy2                   | 344 ms                                                 | 397 ms: 1.15x slower                                                      |
| dask                    | 365 ms                                                 | 524 ms: 1.44x slower                                                      |
| xml_etree_parse         | 154 ms                                                 | 346 ms: 2.25x slower                                                      |
| xml_etree_iterparse     | 104 ms                                                 | 323 ms: 3.11x slower                                                      |
| Geometric mean          | (ref)                                                  | 1.01x slower                                                              |

Benchmark hidden because not significant (15): pycparser, regex_dna, pyflate, pickle, json, typing_runtime_protocols, unpickle, sqlite_synth, tornado_http, bench_mp_pool, meteor_contest, mako, pickle_list, json_loads, deepcopy_reduce
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.73% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
