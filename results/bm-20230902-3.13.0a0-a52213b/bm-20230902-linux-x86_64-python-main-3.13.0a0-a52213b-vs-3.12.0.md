
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.00x faster
- HPT reliability: 98.59%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.62 sec: 1.03x faster                                |
| tornado_http   | 99.6 ms                                                | 95.0 ms: 1.05x faster                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 80.7 ms                                                | 78.7 ms: 1.03x faster                                 |
| nbody          | 88.8 ms                                                | 89.3 ms: 1.01x slower                                 |
| pidigits       | 187 ms                                                 | 203 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 135 ms: 1.06x faster                                  |
| regex_effbot   | 3.55 ms                                                | 3.68 ms: 1.04x slower                                 |
| regex_dna      | 209 ms                                                 | 221 ms: 1.06x slower                                  |
| regex_v8       | 22.3 ms                                                | 24.6 ms: 1.10x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| unpickle             | 15.0 us                                                | 13.8 us: 1.08x faster                                 |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                |
| pickle_pure_python   | 309 us                                                 | 297 us: 1.04x faster                                  |
| xml_etree_process    | 58.6 ms                                                | 56.6 ms: 1.04x faster                                 |
| xml_etree_generate   | 84.8 ms                                                | 82.0 ms: 1.03x faster                                 |
| xml_etree_parse      | 154 ms                                                 | 150 ms: 1.02x faster                                  |
| unpickle_pure_python | 218 us                                                 | 213 us: 1.02x faster                                  |
| unpickle_list        | 4.95 us                                                | 4.84 us: 1.02x faster                                 |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                 |
| json_dumps           | 9.85 ms                                                | 9.91 ms: 1.01x slower                                 |
| pickle_list          | 4.62 us                                                | 4.74 us: 1.03x slower                                 |
| pickle_dict          | 31.6 us                                                | 32.6 us: 1.03x slower                                 |
| Geometric mean       | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.43 ms: 1.00x faster                                 |
| python_startup_no_site | 6.90 ms                                                | 6.93 ms: 1.00x slower                                 |
| Geometric mean         | (ref)                                                  | 1.00x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.0 ms: 1.03x slower                                 |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230902-linux-x86_64-python-main-3.13.0a0-a52213b |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| crypto_pyaes            | 77.2 ms                                                | 70.3 ms: 1.10x faster                                 |
| asyncio_tcp             | 526 ms                                                 | 485 ms: 1.08x faster                                  |
| coverage                | 94.2 ms                                                | 86.9 ms: 1.08x faster                                 |
| deltablue               | 3.52 ms                                                | 3.25 ms: 1.08x faster                                 |
| unpickle                | 15.0 us                                                | 13.8 us: 1.08x faster                                 |
| generators              | 31.1 ms                                                | 28.9 ms: 1.08x faster                                 |
| async_tree_none         | 469 ms                                                 | 438 ms: 1.07x faster                                  |
| scimark_monte_carlo     | 71.0 ms                                                | 66.4 ms: 1.07x faster                                 |
| logging_format          | 6.90 us                                                | 6.48 us: 1.07x faster                                 |
| raytrace                | 294 ms                                                 | 276 ms: 1.07x faster                                  |
| chaos                   | 63.5 ms                                                | 59.7 ms: 1.07x faster                                 |
| regex_compile           | 144 ms                                                 | 135 ms: 1.06x faster                                  |
| scimark_sor             | 125 ms                                                 | 118 ms: 1.05x faster                                  |
| logging_simple          | 6.18 us                                                | 5.87 us: 1.05x faster                                 |
| scimark_lu              | 114 ms                                                 | 109 ms: 1.05x faster                                  |
| tornado_http            | 99.6 ms                                                | 95.0 ms: 1.05x faster                                 |
| tomli_loads             | 2.22 sec                                               | 2.12 sec: 1.05x faster                                |
| sqlglot_parse           | 1.32 ms                                                | 1.27 ms: 1.04x faster                                 |
| sqlglot_transpile       | 1.64 ms                                                | 1.57 ms: 1.04x faster                                 |
| pickle_pure_python      | 309 us                                                 | 297 us: 1.04x faster                                  |
| xml_etree_process       | 58.6 ms                                                | 56.6 ms: 1.04x faster                                 |
| xml_etree_generate      | 84.8 ms                                                | 82.0 ms: 1.03x faster                                 |
| docutils                | 2.70 sec                                               | 2.62 sec: 1.03x faster                                |
| deepcopy                | 355 us                                                 | 345 us: 1.03x faster                                  |
| sqlglot_normalize       | 107 ms                                                 | 104 ms: 1.03x faster                                  |
| float                   | 80.7 ms                                                | 78.7 ms: 1.03x faster                                 |
| xml_etree_parse         | 154 ms                                                 | 150 ms: 1.02x faster                                  |
| unpickle_pure_python    | 218 us                                                 | 213 us: 1.02x faster                                  |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.64 ms: 1.02x faster                                 |
| create_gc_cycles        | 1.52 ms                                                | 1.49 ms: 1.02x faster                                 |
| unpickle_list           | 4.95 us                                                | 4.84 us: 1.02x faster                                 |
| nqueens                 | 81.1 ms                                                | 79.6 ms: 1.02x faster                                 |
| pyflate                 | 450 ms                                                 | 442 ms: 1.02x faster                                  |
| hexiom                  | 6.12 ms                                                | 6.01 ms: 1.02x faster                                 |
| dulwich_log             | 67.9 ms                                                | 66.7 ms: 1.02x faster                                 |
| xml_etree_iterparse     | 104 ms                                                 | 102 ms: 1.02x faster                                  |
| sqlglot_optimize        | 53.3 ms                                                | 52.4 ms: 1.02x faster                                 |
| mypy2                   | 344 ms                                                 | 339 ms: 1.02x faster                                  |
| deepcopy_reduce         | 3.14 us                                                | 3.09 us: 1.01x faster                                 |
| fannkuch                | 387 ms                                                 | 382 ms: 1.01x faster                                  |
| deepcopy_memo           | 37.4 us                                                | 36.9 us: 1.01x faster                                 |
| async_tree_cpu_io_mixed | 714 ms                                                 | 705 ms: 1.01x faster                                  |
| pickle                  | 10.6 us                                                | 10.5 us: 1.01x faster                                 |
| scimark_fft             | 358 ms                                                 | 355 ms: 1.01x faster                                  |
| bench_thread_pool       | 827 us                                                 | 819 us: 1.01x faster                                  |
| pprint_pformat          | 1.50 sec                                               | 1.49 sec: 1.01x faster                                |
| coroutines              | 22.4 ms                                                | 22.2 ms: 1.01x faster                                 |
| pprint_safe_repr        | 735 ms                                                 | 730 ms: 1.01x faster                                  |
| python_startup          | 9.47 ms                                                | 9.43 ms: 1.00x faster                                 |
| python_startup_no_site  | 6.90 ms                                                | 6.93 ms: 1.00x slower                                 |
| nbody                   | 88.8 ms                                                | 89.3 ms: 1.01x slower                                 |
| json_dumps              | 9.85 ms                                                | 9.91 ms: 1.01x slower                                 |
| comprehensions          | 20.4 us                                                | 20.7 us: 1.01x slower                                 |
| meteor_contest          | 105 ms                                                 | 106 ms: 1.01x slower                                  |
| pathlib                 | 18.5 ms                                                | 18.8 ms: 1.02x slower                                 |
| async_generators        | 440 ms                                                 | 448 ms: 1.02x slower                                  |
| unpack_sequence         | 44.8 ns                                                | 45.7 ns: 1.02x slower                                 |
| go                      | 136 ms                                                 | 138 ms: 1.02x slower                                  |
| spectral_norm           | 106 ms                                                 | 108 ms: 1.02x slower                                  |
| pickle_list             | 4.62 us                                                | 4.74 us: 1.03x slower                                 |
| mako                    | 10.7 ms                                                | 11.0 ms: 1.03x slower                                 |
| pickle_dict             | 31.6 us                                                | 32.6 us: 1.03x slower                                 |
| async_tree_io           | 1.16 sec                                               | 1.19 sec: 1.03x slower                                |
| json                    | 4.77 ms                                                | 4.94 ms: 1.04x slower                                 |
| regex_effbot            | 3.55 ms                                                | 3.68 ms: 1.04x slower                                 |
| logging_silent          | 99.1 ns                                                | 103 ns: 1.04x slower                                  |
| pycparser               | 1.15 sec                                               | 1.20 sec: 1.04x slower                                |
| regex_dna               | 209 ms                                                 | 221 ms: 1.06x slower                                  |
| mdp                     | 2.57 sec                                               | 2.73 sec: 1.06x slower                                |
| pidigits                | 187 ms                                                 | 203 ms: 1.09x slower                                  |
| richards_super          | 49.0 ms                                                | 53.3 ms: 1.09x slower                                 |
| gc_traversal            | 3.84 ms                                                | 4.18 ms: 1.09x slower                                 |
| richards                | 43.2 ms                                                | 47.0 ms: 1.09x slower                                 |
| regex_v8                | 22.3 ms                                                | 24.6 ms: 1.10x slower                                 |
| telco                   | 6.87 ms                                                | 8.00 ms: 1.16x slower                                 |
| dask                    | 365 ms                                                 | 523 ms: 1.43x slower                                  |
| Geometric mean          | (ref)                                                  | 1.00x faster                                          |

Benchmark hidden because not significant (6): async_tree_memoization, typing_runtime_protocols, asyncio_tcp_ssl, bench_mp_pool, sqlite_synth, json_loads
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.59% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
