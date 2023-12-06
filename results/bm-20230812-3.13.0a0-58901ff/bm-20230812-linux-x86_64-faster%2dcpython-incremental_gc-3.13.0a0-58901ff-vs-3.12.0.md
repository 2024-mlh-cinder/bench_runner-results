
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 58901ff
- commit date: 2023-08-12
- overall geometric mean: 1.04x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-58901ff |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.39 sec: 1.13x faster                                                    |
| tornado_http   | 99.6 ms                                                | 93.5 ms: 1.07x faster                                                     |
| Geometric mean | (ref)                                                  | 1.10x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-58901ff |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 71.9 ms: 1.12x faster                                                     |
| nbody          | 88.8 ms                                                | 89.8 ms: 1.01x slower                                                     |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| Geometric mean | (ref)                                                  | 1.03x faster                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-58901ff |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| regex_effbot   | 3.55 ms                                                | 3.46 ms: 1.02x faster                                                     |
| regex_v8       | 22.3 ms                                                | 22.7 ms: 1.01x slower                                                     |
| Geometric mean | (ref)                                                  | 1.01x faster                                                              |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-58901ff |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| xml_etree_iterparse  | 104 ms                                                 | 93.8 ms: 1.11x faster                                                     |
| xml_etree_parse      | 154 ms                                                 | 141 ms: 1.09x faster                                                      |
| pickle_pure_python   | 309 us                                                 | 294 us: 1.05x faster                                                      |
| xml_etree_generate   | 84.8 ms                                                | 80.9 ms: 1.05x faster                                                     |
| xml_etree_process    | 58.6 ms                                                | 56.4 ms: 1.04x faster                                                     |
| unpickle_pure_python | 218 us                                                 | 212 us: 1.03x faster                                                      |
| pickle_dict          | 31.6 us                                                | 30.9 us: 1.02x faster                                                     |
| pickle_list          | 4.62 us                                                | 4.51 us: 1.02x faster                                                     |
| pickle               | 10.6 us                                                | 10.4 us: 1.02x faster                                                     |
| json_dumps           | 9.85 ms                                                | 9.75 ms: 1.01x faster                                                     |
| json_loads           | 25.2 us                                                | 25.6 us: 1.01x slower                                                     |
| unpickle_list        | 4.95 us                                                | 5.08 us: 1.03x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.28 sec: 1.03x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.03x faster                                                              |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-58901ff |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.28 ms: 1.02x faster                                                     |
| python_startup_no_site | 6.90 ms                                                | 6.81 ms: 1.01x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-58901ff |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                     |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-58901ff |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io           | 1.16 sec                                               | 561 ms: 2.06x faster                                                      |
| async_tree_none         | 469 ms                                                 | 276 ms: 1.70x faster                                                      |
| async_tree_memoization  | 573 ms                                                 | 342 ms: 1.68x faster                                                      |
| async_tree_cpu_io_mixed | 714 ms                                                 | 503 ms: 1.42x faster                                                      |
| docutils                | 2.70 sec                                               | 2.39 sec: 1.13x faster                                                    |
| deltablue               | 3.52 ms                                                | 3.12 ms: 1.13x faster                                                     |
| float                   | 80.7 ms                                                | 71.9 ms: 1.12x faster                                                     |
| crypto_pyaes            | 77.2 ms                                                | 69.4 ms: 1.11x faster                                                     |
| generators              | 31.1 ms                                                | 28.1 ms: 1.11x faster                                                     |
| xml_etree_iterparse     | 104 ms                                                 | 93.8 ms: 1.11x faster                                                     |
| raytrace                | 294 ms                                                 | 267 ms: 1.10x faster                                                      |
| xml_etree_parse         | 154 ms                                                 | 141 ms: 1.09x faster                                                      |
| asyncio_tcp             | 526 ms                                                 | 485 ms: 1.08x faster                                                      |
| chaos                   | 63.5 ms                                                | 59.0 ms: 1.08x faster                                                     |
| logging_format          | 6.90 us                                                | 6.44 us: 1.07x faster                                                     |
| create_gc_cycles        | 1.52 ms                                                | 1.43 ms: 1.07x faster                                                     |
| tornado_http            | 99.6 ms                                                | 93.5 ms: 1.07x faster                                                     |
| scimark_monte_carlo     | 71.0 ms                                                | 67.1 ms: 1.06x faster                                                     |
| regex_compile           | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| pycparser               | 1.15 sec                                               | 1.09 sec: 1.06x faster                                                    |
| pickle_pure_python      | 309 us                                                 | 294 us: 1.05x faster                                                      |
| logging_simple          | 6.18 us                                                | 5.88 us: 1.05x faster                                                     |
| xml_etree_generate      | 84.8 ms                                                | 80.9 ms: 1.05x faster                                                     |
| xml_etree_process       | 58.6 ms                                                | 56.4 ms: 1.04x faster                                                     |
| scimark_sor             | 125 ms                                                 | 120 ms: 1.04x faster                                                      |
| scimark_lu              | 114 ms                                                 | 110 ms: 1.04x faster                                                      |
| sqlglot_parse           | 1.32 ms                                                | 1.28 ms: 1.04x faster                                                     |
| async_generators        | 440 ms                                                 | 426 ms: 1.03x faster                                                      |
| hexiom                  | 6.12 ms                                                | 5.93 ms: 1.03x faster                                                     |
| unpickle_pure_python    | 218 us                                                 | 212 us: 1.03x faster                                                      |
| dulwich_log             | 67.9 ms                                                | 65.9 ms: 1.03x faster                                                     |
| sqlglot_transpile       | 1.64 ms                                                | 1.59 ms: 1.03x faster                                                     |
| sqlglot_normalize       | 107 ms                                                 | 104 ms: 1.03x faster                                                      |
| pprint_safe_repr        | 735 ms                                                 | 716 ms: 1.03x faster                                                      |
| regex_effbot            | 3.55 ms                                                | 3.46 ms: 1.02x faster                                                     |
| pickle_dict             | 31.6 us                                                | 30.9 us: 1.02x faster                                                     |
| pickle_list             | 4.62 us                                                | 4.51 us: 1.02x faster                                                     |
| pprint_pformat          | 1.50 sec                                               | 1.47 sec: 1.02x faster                                                    |
| python_startup          | 9.47 ms                                                | 9.28 ms: 1.02x faster                                                     |
| pickle                  | 10.6 us                                                | 10.4 us: 1.02x faster                                                     |
| gc_traversal            | 3.84 ms                                                | 3.78 ms: 1.02x faster                                                     |
| comprehensions          | 20.4 us                                                | 20.1 us: 1.02x faster                                                     |
| mypy2                   | 344 ms                                                 | 338 ms: 1.02x faster                                                      |
| nqueens                 | 81.1 ms                                                | 79.9 ms: 1.02x faster                                                     |
| coverage                | 94.2 ms                                                | 92.8 ms: 1.01x faster                                                     |
| mdp                     | 2.57 sec                                               | 2.53 sec: 1.01x faster                                                    |
| sqlglot_optimize        | 53.3 ms                                                | 52.6 ms: 1.01x faster                                                     |
| python_startup_no_site  | 6.90 ms                                                | 6.81 ms: 1.01x faster                                                     |
| json_dumps              | 9.85 ms                                                | 9.75 ms: 1.01x faster                                                     |
| pyflate                 | 450 ms                                                 | 446 ms: 1.01x faster                                                      |
| coroutines              | 22.4 ms                                                | 22.3 ms: 1.01x faster                                                     |
| asyncio_tcp_ssl         | 1.79 sec                                               | 1.78 sec: 1.01x faster                                                    |
| bench_thread_pool       | 827 us                                                 | 824 us: 1.00x faster                                                      |
| mako                    | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                     |
| deepcopy_memo           | 37.4 us                                                | 37.7 us: 1.01x slower                                                     |
| pathlib                 | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                     |
| nbody                   | 88.8 ms                                                | 89.8 ms: 1.01x slower                                                     |
| fannkuch                | 387 ms                                                 | 392 ms: 1.01x slower                                                      |
| pidigits                | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| json_loads              | 25.2 us                                                | 25.6 us: 1.01x slower                                                     |
| regex_v8                | 22.3 ms                                                | 22.7 ms: 1.01x slower                                                     |
| logging_silent          | 99.1 ns                                                | 101 ns: 1.01x slower                                                      |
| go                      | 136 ms                                                 | 138 ms: 1.02x slower                                                      |
| meteor_contest          | 105 ms                                                 | 107 ms: 1.02x slower                                                      |
| spectral_norm           | 106 ms                                                 | 108 ms: 1.02x slower                                                      |
| deepcopy_reduce         | 3.14 us                                                | 3.22 us: 1.03x slower                                                     |
| unpickle_list           | 4.95 us                                                | 5.08 us: 1.03x slower                                                     |
| tomli_loads             | 2.22 sec                                               | 2.28 sec: 1.03x slower                                                    |
| unpack_sequence         | 44.8 ns                                                | 46.2 ns: 1.03x slower                                                     |
| richards_super          | 49.0 ms                                                | 53.8 ms: 1.10x slower                                                     |
| richards                | 43.2 ms                                                | 48.2 ms: 1.12x slower                                                     |
| telco                   | 6.87 ms                                                | 7.92 ms: 1.15x slower                                                     |
| dask                    | 365 ms                                                 | 489 ms: 1.34x slower                                                      |
| Geometric mean          | (ref)                                                  | 1.04x faster                                                              |

Benchmark hidden because not significant (9): scimark_fft, sqlite_synth, typing_runtime_protocols, deepcopy, scimark_sparse_mat_mult, bench_mp_pool, unpickle, json, regex_dna
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
