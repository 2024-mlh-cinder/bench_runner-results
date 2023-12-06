
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 7bb5172
- commit date: 2023-09-09
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.73 sec: 1.01x slower                                                  |
| tornado_http   | 99.6 ms                                                | 97.7 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                  | 1.00x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                    |
| float          | 80.7 ms                                                | 84.3 ms: 1.04x slower                                                   |
| nbody          | 88.8 ms                                                | 137 ms: 1.54x slower                                                    |
| Geometric mean | (ref)                                                  | 1.18x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 150 ms: 1.04x slower                                                    |
| regex_dna      | 209 ms                                                 | 218 ms: 1.05x slower                                                    |
| regex_effbot   | 3.55 ms                                                | 3.75 ms: 1.06x slower                                                   |
| regex_v8       | 22.3 ms                                                | 25.5 ms: 1.14x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.7 us: 1.02x faster                                                   |
| pickle_pure_python   | 309 us                                                 | 305 us: 1.01x faster                                                    |
| unpickle_list        | 4.95 us                                                | 4.89 us: 1.01x faster                                                   |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                    |
| json_loads           | 25.2 us                                                | 25.1 us: 1.01x faster                                                   |
| pickle_list          | 4.62 us                                                | 4.68 us: 1.01x slower                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                    |
| pickle               | 10.6 us                                                | 10.8 us: 1.01x slower                                                   |
| json_dumps           | 9.85 ms                                                | 9.99 ms: 1.01x slower                                                   |
| pickle_dict          | 31.6 us                                                | 32.1 us: 1.02x slower                                                   |
| tomli_loads          | 2.22 sec                                               | 2.29 sec: 1.03x slower                                                  |
| xml_etree_generate   | 84.8 ms                                                | 88.2 ms: 1.04x slower                                                   |
| unpickle_pure_python | 218 us                                                 | 238 us: 1.09x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (1): xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.58 ms: 1.01x slower                                                   |
| python_startup_no_site | 6.90 ms                                                | 7.04 ms: 1.02x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 13.9 ms: 1.30x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230909-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7bb5172 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 86.6 ms: 1.09x faster                                                   |
| asyncio_tcp              | 526 ms                                                 | 494 ms: 1.06x faster                                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 67.7 ms: 1.05x faster                                                   |
| async_tree_none          | 469 ms                                                 | 451 ms: 1.04x faster                                                    |
| crypto_pyaes             | 77.2 ms                                                | 74.2 ms: 1.04x faster                                                   |
| logging_format           | 6.90 us                                                | 6.67 us: 1.04x faster                                                   |
| raytrace                 | 294 ms                                                 | 287 ms: 1.03x faster                                                    |
| generators               | 31.1 ms                                                | 30.3 ms: 1.02x faster                                                   |
| logging_simple           | 6.18 us                                                | 6.03 us: 1.02x faster                                                   |
| tornado_http             | 99.6 ms                                                | 97.7 ms: 1.02x faster                                                   |
| unpickle                 | 15.0 us                                                | 14.7 us: 1.02x faster                                                   |
| sqlglot_parse            | 1.32 ms                                                | 1.30 ms: 1.02x faster                                                   |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                                   |
| pickle_pure_python       | 309 us                                                 | 305 us: 1.01x faster                                                    |
| unpickle_list            | 4.95 us                                                | 4.89 us: 1.01x faster                                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.62 ms: 1.01x faster                                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                                   |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                                   |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                    |
| json_loads               | 25.2 us                                                | 25.1 us: 1.01x faster                                                   |
| gc_traversal             | 3.84 ms                                                | 3.84 ms: 1.00x faster                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                                  |
| docutils                 | 2.70 sec                                               | 2.73 sec: 1.01x slower                                                  |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                    |
| python_startup           | 9.47 ms                                                | 9.58 ms: 1.01x slower                                                   |
| async_tree_memoization   | 573 ms                                                 | 580 ms: 1.01x slower                                                    |
| pickle_list              | 4.62 us                                                | 4.68 us: 1.01x slower                                                   |
| dulwich_log              | 67.9 ms                                                | 68.9 ms: 1.01x slower                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                    |
| pickle                   | 10.6 us                                                | 10.8 us: 1.01x slower                                                   |
| json_dumps               | 9.85 ms                                                | 9.99 ms: 1.01x slower                                                   |
| pickle_dict              | 31.6 us                                                | 32.1 us: 1.02x slower                                                   |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.02x slower                                                   |
| sqlglot_normalize        | 107 ms                                                 | 109 ms: 1.02x slower                                                    |
| python_startup_no_site   | 6.90 ms                                                | 7.04 ms: 1.02x slower                                                   |
| scimark_lu               | 114 ms                                                 | 117 ms: 1.03x slower                                                    |
| deltablue                | 3.52 ms                                                | 3.62 ms: 1.03x slower                                                   |
| pycparser                | 1.15 sec                                               | 1.18 sec: 1.03x slower                                                  |
| bench_thread_pool        | 827 us                                                 | 853 us: 1.03x slower                                                    |
| tomli_loads              | 2.22 sec                                               | 2.29 sec: 1.03x slower                                                  |
| mdp                      | 2.57 sec                                               | 2.65 sec: 1.03x slower                                                  |
| xml_etree_generate       | 84.8 ms                                                | 88.2 ms: 1.04x slower                                                   |
| scimark_sor              | 125 ms                                                 | 130 ms: 1.04x slower                                                    |
| regex_compile            | 144 ms                                                 | 150 ms: 1.04x slower                                                    |
| pprint_safe_repr         | 735 ms                                                 | 767 ms: 1.04x slower                                                    |
| float                    | 80.7 ms                                                | 84.3 ms: 1.04x slower                                                   |
| regex_dna                | 209 ms                                                 | 218 ms: 1.05x slower                                                    |
| pprint_pformat           | 1.50 sec                                               | 1.57 sec: 1.05x slower                                                  |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.05x slower                                                  |
| sqlglot_optimize         | 53.3 ms                                                | 56.0 ms: 1.05x slower                                                   |
| deepcopy                 | 355 us                                                 | 376 us: 1.06x slower                                                    |
| regex_effbot             | 3.55 ms                                                | 3.75 ms: 1.06x slower                                                   |
| spectral_norm            | 106 ms                                                 | 113 ms: 1.06x slower                                                    |
| mypy2                    | 344 ms                                                 | 364 ms: 1.06x slower                                                    |
| chaos                    | 63.5 ms                                                | 67.7 ms: 1.06x slower                                                   |
| scimark_fft              | 358 ms                                                 | 382 ms: 1.06x slower                                                    |
| pyflate                  | 450 ms                                                 | 484 ms: 1.07x slower                                                    |
| meteor_contest           | 105 ms                                                 | 113 ms: 1.08x slower                                                    |
| async_generators         | 440 ms                                                 | 476 ms: 1.08x slower                                                    |
| logging_silent           | 99.1 ns                                                | 108 ns: 1.09x slower                                                    |
| unpickle_pure_python     | 218 us                                                 | 238 us: 1.09x slower                                                    |
| fannkuch                 | 387 ms                                                 | 429 ms: 1.11x slower                                                    |
| typing_runtime_protocols | 146 us                                                 | 162 us: 1.11x slower                                                    |
| go                       | 136 ms                                                 | 152 ms: 1.12x slower                                                    |
| richards_super           | 49.0 ms                                                | 55.9 ms: 1.14x slower                                                   |
| richards                 | 43.2 ms                                                | 49.3 ms: 1.14x slower                                                   |
| regex_v8                 | 22.3 ms                                                | 25.5 ms: 1.14x slower                                                   |
| nqueens                  | 81.1 ms                                                | 96.9 ms: 1.19x slower                                                   |
| hexiom                   | 6.12 ms                                                | 7.38 ms: 1.21x slower                                                   |
| telco                    | 6.87 ms                                                | 8.35 ms: 1.21x slower                                                   |
| unpack_sequence          | 44.8 ns                                                | 55.9 ns: 1.25x slower                                                   |
| mako                     | 10.7 ms                                                | 13.9 ms: 1.30x slower                                                   |
| comprehensions           | 20.4 us                                                | 27.9 us: 1.37x slower                                                   |
| deepcopy_memo            | 37.4 us                                                | 51.5 us: 1.38x slower                                                   |
| dask                     | 365 ms                                                 | 539 ms: 1.48x slower                                                    |
| nbody                    | 88.8 ms                                                | 137 ms: 1.54x slower                                                    |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 9.20 ms: 1.94x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.06x slower                                                            |

Benchmark hidden because not significant (5): xml_etree_process, bench_mp_pool, deepcopy_reduce, async_tree_cpu_io_mixed, json
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
