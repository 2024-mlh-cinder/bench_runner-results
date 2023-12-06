
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: af24cd7
- commit date: 2023-08-12
- overall geometric mean: 1.02x faster
- HPT reliability: 99.71%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark    | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-af24cd7 |
|--------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| tornado_http | 99.6 ms                                                | 92.9 ms: 1.07x faster                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-af24cd7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 76.8 ms: 1.05x faster                                                     |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| Geometric mean | (ref)                                                  | 1.01x faster                                                              |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-af24cd7 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| regex_v8       | 22.3 ms                                                | 22.3 ms: 1.00x faster                                                     |
| regex_effbot   | 3.55 ms                                                | 3.73 ms: 1.05x slower                                                     |
| Geometric mean | (ref)                                                  | 1.00x faster                                                              |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-af24cd7 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 293 us: 1.06x faster                                                      |
| xml_etree_process    | 58.6 ms                                                | 57.3 ms: 1.02x faster                                                     |
| xml_etree_generate   | 84.8 ms                                                | 83.3 ms: 1.02x faster                                                     |
| unpickle_pure_python | 218 us                                                 | 215 us: 1.01x faster                                                      |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                                     |
| json_loads           | 25.2 us                                                | 25.4 us: 1.01x slower                                                     |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                      |
| json_dumps           | 9.85 ms                                                | 10.0 ms: 1.02x slower                                                     |
| pickle_list          | 4.62 us                                                | 4.70 us: 1.02x slower                                                     |
| unpickle_list        | 4.95 us                                                | 5.08 us: 1.03x slower                                                     |
| pickle_dict          | 31.6 us                                                | 32.7 us: 1.03x slower                                                     |
| xml_etree_parse      | 154 ms                                                 | 168 ms: 1.10x slower                                                      |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                              |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-af24cd7 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.75 ms: 1.02x faster                                                     |
| python_startup         | 9.47 ms                                                | 9.29 ms: 1.02x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-af24cd7 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io           | 1.16 sec                                               | 717 ms: 1.61x faster                                                      |
| async_tree_memoization  | 573 ms                                                 | 406 ms: 1.41x faster                                                      |
| async_tree_none         | 469 ms                                                 | 341 ms: 1.38x faster                                                      |
| async_tree_cpu_io_mixed | 714 ms                                                 | 575 ms: 1.24x faster                                                      |
| deltablue               | 3.52 ms                                                | 3.16 ms: 1.11x faster                                                     |
| crypto_pyaes            | 77.2 ms                                                | 69.6 ms: 1.11x faster                                                     |
| raytrace                | 294 ms                                                 | 266 ms: 1.11x faster                                                      |
| generators              | 31.1 ms                                                | 28.2 ms: 1.10x faster                                                     |
| asyncio_tcp             | 526 ms                                                 | 485 ms: 1.08x faster                                                      |
| scimark_monte_carlo     | 71.0 ms                                                | 66.1 ms: 1.07x faster                                                     |
| tornado_http            | 99.6 ms                                                | 92.9 ms: 1.07x faster                                                     |
| logging_format          | 6.90 us                                                | 6.44 us: 1.07x faster                                                     |
| chaos                   | 63.5 ms                                                | 59.4 ms: 1.07x faster                                                     |
| gc_traversal            | 3.84 ms                                                | 3.60 ms: 1.07x faster                                                     |
| create_gc_cycles        | 1.52 ms                                                | 1.44 ms: 1.06x faster                                                     |
| regex_compile           | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| pickle_pure_python      | 309 us                                                 | 293 us: 1.06x faster                                                      |
| float                   | 80.7 ms                                                | 76.8 ms: 1.05x faster                                                     |
| logging_simple          | 6.18 us                                                | 5.89 us: 1.05x faster                                                     |
| sqlglot_transpile       | 1.64 ms                                                | 1.58 ms: 1.04x faster                                                     |
| sqlglot_parse           | 1.32 ms                                                | 1.28 ms: 1.03x faster                                                     |
| scimark_sor             | 125 ms                                                 | 121 ms: 1.03x faster                                                      |
| pprint_safe_repr        | 735 ms                                                 | 716 ms: 1.03x faster                                                      |
| scimark_lu              | 114 ms                                                 | 111 ms: 1.02x faster                                                      |
| pyflate                 | 450 ms                                                 | 440 ms: 1.02x faster                                                      |
| pprint_pformat          | 1.50 sec                                               | 1.47 sec: 1.02x faster                                                    |
| python_startup_no_site  | 6.90 ms                                                | 6.75 ms: 1.02x faster                                                     |
| xml_etree_process       | 58.6 ms                                                | 57.3 ms: 1.02x faster                                                     |
| dulwich_log             | 67.9 ms                                                | 66.5 ms: 1.02x faster                                                     |
| python_startup          | 9.47 ms                                                | 9.29 ms: 1.02x faster                                                     |
| hexiom                  | 6.12 ms                                                | 6.01 ms: 1.02x faster                                                     |
| nqueens                 | 81.1 ms                                                | 79.6 ms: 1.02x faster                                                     |
| xml_etree_generate      | 84.8 ms                                                | 83.3 ms: 1.02x faster                                                     |
| coverage                | 94.2 ms                                                | 92.6 ms: 1.02x faster                                                     |
| scimark_fft             | 358 ms                                                 | 353 ms: 1.02x faster                                                      |
| unpickle_pure_python    | 218 us                                                 | 215 us: 1.01x faster                                                      |
| pickle                  | 10.6 us                                                | 10.5 us: 1.01x faster                                                     |
| comprehensions          | 20.4 us                                                | 20.2 us: 1.01x faster                                                     |
| logging_silent          | 99.1 ns                                                | 98.1 ns: 1.01x faster                                                     |
| sqlglot_normalize       | 107 ms                                                 | 106 ms: 1.01x faster                                                      |
| coroutines              | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                     |
| async_generators        | 440 ms                                                 | 437 ms: 1.01x faster                                                      |
| asyncio_tcp_ssl         | 1.79 sec                                               | 1.78 sec: 1.01x faster                                                    |
| bench_thread_pool       | 827 us                                                 | 824 us: 1.00x faster                                                      |
| regex_v8                | 22.3 ms                                                | 22.3 ms: 1.00x faster                                                     |
| json_loads              | 25.2 us                                                | 25.4 us: 1.01x slower                                                     |
| pathlib                 | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                     |
| deepcopy_memo           | 37.4 us                                                | 37.8 us: 1.01x slower                                                     |
| xml_etree_iterparse     | 104 ms                                                 | 105 ms: 1.01x slower                                                      |
| json                    | 4.77 ms                                                | 4.83 ms: 1.01x slower                                                     |
| pidigits                | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| go                      | 136 ms                                                 | 138 ms: 1.01x slower                                                      |
| meteor_contest          | 105 ms                                                 | 106 ms: 1.02x slower                                                      |
| json_dumps              | 9.85 ms                                                | 10.0 ms: 1.02x slower                                                     |
| deepcopy_reduce         | 3.14 us                                                | 3.19 us: 1.02x slower                                                     |
| pickle_list             | 4.62 us                                                | 4.70 us: 1.02x slower                                                     |
| fannkuch                | 387 ms                                                 | 396 ms: 1.02x slower                                                      |
| unpack_sequence         | 44.8 ns                                                | 46.0 ns: 1.03x slower                                                     |
| unpickle_list           | 4.95 us                                                | 5.08 us: 1.03x slower                                                     |
| mdp                     | 2.57 sec                                               | 2.65 sec: 1.03x slower                                                    |
| pickle_dict             | 31.6 us                                                | 32.7 us: 1.03x slower                                                     |
| mypy2                   | 344 ms                                                 | 359 ms: 1.04x slower                                                      |
| regex_effbot            | 3.55 ms                                                | 3.73 ms: 1.05x slower                                                     |
| richards_super          | 49.0 ms                                                | 53.3 ms: 1.09x slower                                                     |
| richards                | 43.2 ms                                                | 47.2 ms: 1.09x slower                                                     |
| xml_etree_parse         | 154 ms                                                 | 168 ms: 1.10x slower                                                      |
| telco                   | 6.87 ms                                                | 7.95 ms: 1.16x slower                                                     |
| dask                    | 365 ms                                                 | 499 ms: 1.37x slower                                                      |
| Geometric mean          | (ref)                                                  | 1.02x faster                                                              |

Benchmark hidden because not significant (11): scimark_sparse_mat_mult, typing_runtime_protocols, unpickle, mako, nbody, deepcopy, bench_mp_pool, sqlite_synth, spectral_norm, sqlglot_optimize, regex_dna
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, docutils, pycparser, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads


# HPT report

- Reliability score: 99.71% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
