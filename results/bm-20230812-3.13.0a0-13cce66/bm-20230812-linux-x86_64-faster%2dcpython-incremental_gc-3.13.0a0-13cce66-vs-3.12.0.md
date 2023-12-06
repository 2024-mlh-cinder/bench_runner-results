
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 13cce66
- commit date: 2023-08-12
- overall geometric mean: 1.04x faster
- HPT reliability: 99.91%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-13cce66 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.40 sec: 1.13x faster                                                    |
| tornado_http   | 99.6 ms                                                | 94.4 ms: 1.06x faster                                                     |
| Geometric mean | (ref)                                                  | 1.09x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-13cce66 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 72.7 ms: 1.11x faster                                                     |
| nbody          | 88.8 ms                                                | 89.9 ms: 1.01x slower                                                     |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| Geometric mean | (ref)                                                  | 1.03x faster                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-13cce66 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| regex_v8       | 22.3 ms                                                | 22.5 ms: 1.01x slower                                                     |
| regex_effbot   | 3.55 ms                                                | 3.72 ms: 1.05x slower                                                     |
| Geometric mean | (ref)                                                  | 1.00x slower                                                              |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-13cce66 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| xml_etree_iterparse  | 104 ms                                                 | 94.5 ms: 1.10x faster                                                     |
| xml_etree_parse      | 154 ms                                                 | 140 ms: 1.09x faster                                                      |
| xml_etree_generate   | 84.8 ms                                                | 81.8 ms: 1.04x faster                                                     |
| pickle_pure_python   | 309 us                                                 | 298 us: 1.04x faster                                                      |
| xml_etree_process    | 58.6 ms                                                | 56.7 ms: 1.03x faster                                                     |
| unpickle_pure_python | 218 us                                                 | 214 us: 1.02x faster                                                      |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                                     |
| pickle_list          | 4.62 us                                                | 4.58 us: 1.01x faster                                                     |
| pickle_dict          | 31.6 us                                                | 31.8 us: 1.00x slower                                                     |
| json_loads           | 25.2 us                                                | 26.1 us: 1.03x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.34 sec: 1.05x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                              |

Benchmark hidden because not significant (3): json_dumps, unpickle_list, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-13cce66 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.36 ms: 1.01x faster                                                     |
| python_startup_no_site | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.01x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-13cce66 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                     |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-13cce66 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io           | 1.16 sec                                               | 563 ms: 2.06x faster                                                      |
| async_tree_none         | 469 ms                                                 | 276 ms: 1.70x faster                                                      |
| async_tree_memoization  | 573 ms                                                 | 342 ms: 1.68x faster                                                      |
| async_tree_cpu_io_mixed | 714 ms                                                 | 500 ms: 1.43x faster                                                      |
| crypto_pyaes            | 77.2 ms                                                | 68.4 ms: 1.13x faster                                                     |
| docutils                | 2.70 sec                                               | 2.40 sec: 1.13x faster                                                    |
| deltablue               | 3.52 ms                                                | 3.14 ms: 1.12x faster                                                     |
| float                   | 80.7 ms                                                | 72.7 ms: 1.11x faster                                                     |
| xml_etree_iterparse     | 104 ms                                                 | 94.5 ms: 1.10x faster                                                     |
| gc_traversal            | 3.84 ms                                                | 3.51 ms: 1.10x faster                                                     |
| raytrace                | 294 ms                                                 | 269 ms: 1.10x faster                                                      |
| xml_etree_parse         | 154 ms                                                 | 140 ms: 1.09x faster                                                      |
| generators              | 31.1 ms                                                | 28.5 ms: 1.09x faster                                                     |
| asyncio_tcp             | 526 ms                                                 | 482 ms: 1.09x faster                                                      |
| create_gc_cycles        | 1.52 ms                                                | 1.42 ms: 1.07x faster                                                     |
| chaos                   | 63.5 ms                                                | 59.3 ms: 1.07x faster                                                     |
| pycparser               | 1.15 sec                                               | 1.08 sec: 1.07x faster                                                    |
| logging_format          | 6.90 us                                                | 6.52 us: 1.06x faster                                                     |
| scimark_monte_carlo     | 71.0 ms                                                | 67.2 ms: 1.06x faster                                                     |
| tornado_http            | 99.6 ms                                                | 94.4 ms: 1.06x faster                                                     |
| logging_simple          | 6.18 us                                                | 5.89 us: 1.05x faster                                                     |
| regex_compile           | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| xml_etree_generate      | 84.8 ms                                                | 81.8 ms: 1.04x faster                                                     |
| pickle_pure_python      | 309 us                                                 | 298 us: 1.04x faster                                                      |
| sqlglot_parse           | 1.32 ms                                                | 1.28 ms: 1.03x faster                                                     |
| xml_etree_process       | 58.6 ms                                                | 56.7 ms: 1.03x faster                                                     |
| scimark_sor             | 125 ms                                                 | 121 ms: 1.03x faster                                                      |
| sqlglot_transpile       | 1.64 ms                                                | 1.59 ms: 1.03x faster                                                     |
| unpickle_pure_python    | 218 us                                                 | 214 us: 1.02x faster                                                      |
| coroutines              | 22.4 ms                                                | 22.0 ms: 1.02x faster                                                     |
| unpack_sequence         | 44.8 ns                                                | 44.0 ns: 1.02x faster                                                     |
| dulwich_log             | 67.9 ms                                                | 66.8 ms: 1.02x faster                                                     |
| async_generators        | 440 ms                                                 | 433 ms: 1.02x faster                                                      |
| pprint_safe_repr        | 735 ms                                                 | 723 ms: 1.02x faster                                                      |
| pprint_pformat          | 1.50 sec                                               | 1.48 sec: 1.02x faster                                                    |
| pyflate                 | 450 ms                                                 | 444 ms: 1.01x faster                                                      |
| deepcopy                | 355 us                                                 | 351 us: 1.01x faster                                                      |
| pickle                  | 10.6 us                                                | 10.5 us: 1.01x faster                                                     |
| python_startup          | 9.47 ms                                                | 9.36 ms: 1.01x faster                                                     |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.69 ms: 1.01x faster                                                     |
| scimark_fft             | 358 ms                                                 | 355 ms: 1.01x faster                                                      |
| mypy2                   | 344 ms                                                 | 340 ms: 1.01x faster                                                      |
| scimark_lu              | 114 ms                                                 | 113 ms: 1.01x faster                                                      |
| sqlglot_normalize       | 107 ms                                                 | 106 ms: 1.01x faster                                                      |
| pickle_list             | 4.62 us                                                | 4.58 us: 1.01x faster                                                     |
| coverage                | 94.2 ms                                                | 93.4 ms: 1.01x faster                                                     |
| python_startup_no_site  | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                     |
| sqlglot_optimize        | 53.3 ms                                                | 52.9 ms: 1.01x faster                                                     |
| asyncio_tcp_ssl         | 1.79 sec                                               | 1.78 sec: 1.01x faster                                                    |
| hexiom                  | 6.12 ms                                                | 6.09 ms: 1.01x faster                                                     |
| bench_thread_pool       | 827 us                                                 | 829 us: 1.00x slower                                                      |
| pickle_dict             | 31.6 us                                                | 31.8 us: 1.00x slower                                                     |
| regex_v8                | 22.3 ms                                                | 22.5 ms: 1.01x slower                                                     |
| go                      | 136 ms                                                 | 137 ms: 1.01x slower                                                      |
| nbody                   | 88.8 ms                                                | 89.9 ms: 1.01x slower                                                     |
| deepcopy_memo           | 37.4 us                                                | 37.9 us: 1.01x slower                                                     |
| pidigits                | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| json                    | 4.77 ms                                                | 4.85 ms: 1.02x slower                                                     |
| fannkuch                | 387 ms                                                 | 394 ms: 1.02x slower                                                      |
| mako                    | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                     |
| meteor_contest          | 105 ms                                                 | 107 ms: 1.02x slower                                                      |
| json_loads              | 25.2 us                                                | 26.1 us: 1.03x slower                                                     |
| mdp                     | 2.57 sec                                               | 2.69 sec: 1.05x slower                                                    |
| regex_effbot            | 3.55 ms                                                | 3.72 ms: 1.05x slower                                                     |
| tomli_loads             | 2.22 sec                                               | 2.34 sec: 1.05x slower                                                    |
| logging_silent          | 99.1 ns                                                | 105 ns: 1.06x slower                                                      |
| richards                | 43.2 ms                                                | 46.2 ms: 1.07x slower                                                     |
| richards_super          | 49.0 ms                                                | 52.7 ms: 1.08x slower                                                     |
| telco                   | 6.87 ms                                                | 7.89 ms: 1.15x slower                                                     |
| dask                    | 365 ms                                                 | 485 ms: 1.33x slower                                                      |
| Geometric mean          | (ref)                                                  | 1.04x faster                                                              |

Benchmark hidden because not significant (12): sqlite_synth, bench_mp_pool, json_dumps, unpickle_list, nqueens, comprehensions, regex_dna, deepcopy_reduce, typing_runtime_protocols, pathlib, spectral_norm, unpickle
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.91% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
