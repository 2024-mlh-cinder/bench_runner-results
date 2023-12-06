
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 5424850
- commit date: 2023-09-07
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.72 sec: 1.01x slower                                                  |
| tornado_http   | 99.6 ms                                                | 98.0 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                  | 1.00x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                    |
| float          | 80.7 ms                                                | 82.9 ms: 1.03x slower                                                   |
| nbody          | 88.8 ms                                                | 103 ms: 1.16x slower                                                    |
| Geometric mean | (ref)                                                  | 1.06x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.63 ms: 1.02x slower                                                   |
| regex_compile  | 144 ms                                                 | 147 ms: 1.02x slower                                                    |
| regex_dna      | 209 ms                                                 | 226 ms: 1.08x slower                                                    |
| regex_v8       | 22.3 ms                                                | 25.2 ms: 1.13x slower                                                   |
| Geometric mean | (ref)                                                  | 1.06x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 303 us: 1.02x faster                                                    |
| unpickle             | 15.0 us                                                | 14.8 us: 1.01x faster                                                   |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                    |
| xml_etree_process    | 58.6 ms                                                | 58.3 ms: 1.00x faster                                                   |
| xml_etree_generate   | 84.8 ms                                                | 84.5 ms: 1.00x faster                                                   |
| json_dumps           | 9.85 ms                                                | 9.91 ms: 1.01x slower                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                    |
| pickle_dict          | 31.6 us                                                | 32.2 us: 1.02x slower                                                   |
| tomli_loads          | 2.22 sec                                               | 2.26 sec: 1.02x slower                                                  |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                                   |
| pickle_list          | 4.62 us                                                | 4.83 us: 1.05x slower                                                   |
| unpickle_pure_python | 218 us                                                 | 237 us: 1.09x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (2): unpickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.59 ms: 1.01x slower                                                   |
| python_startup_no_site | 6.90 ms                                                | 7.06 ms: 1.02x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.6 ms: 1.08x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-5424850 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 492 ms: 1.07x faster                                                    |
| crypto_pyaes             | 77.2 ms                                                | 72.7 ms: 1.06x faster                                                   |
| coverage                 | 94.2 ms                                                | 88.9 ms: 1.06x faster                                                   |
| async_tree_none          | 469 ms                                                 | 445 ms: 1.05x faster                                                    |
| gc_traversal             | 3.84 ms                                                | 3.67 ms: 1.05x faster                                                   |
| logging_format           | 6.90 us                                                | 6.62 us: 1.04x faster                                                   |
| raytrace                 | 294 ms                                                 | 283 ms: 1.04x faster                                                    |
| generators               | 31.1 ms                                                | 30.0 ms: 1.04x faster                                                   |
| scimark_monte_carlo      | 71.0 ms                                                | 68.7 ms: 1.03x faster                                                   |
| logging_simple           | 6.18 us                                                | 6.02 us: 1.03x faster                                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.49 ms: 1.02x faster                                                   |
| pickle_pure_python       | 309 us                                                 | 303 us: 1.02x faster                                                    |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                                   |
| tornado_http             | 99.6 ms                                                | 98.0 ms: 1.02x faster                                                   |
| unpickle                 | 15.0 us                                                | 14.8 us: 1.01x faster                                                   |
| sqlglot_parse            | 1.32 ms                                                | 1.30 ms: 1.01x faster                                                   |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                    |
| sqlglot_transpile        | 1.64 ms                                                | 1.62 ms: 1.01x faster                                                   |
| deltablue                | 3.52 ms                                                | 3.49 ms: 1.01x faster                                                   |
| xml_etree_process        | 58.6 ms                                                | 58.3 ms: 1.00x faster                                                   |
| xml_etree_generate       | 84.8 ms                                                | 84.5 ms: 1.00x faster                                                   |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                    |
| json_dumps               | 9.85 ms                                                | 9.91 ms: 1.01x slower                                                   |
| docutils                 | 2.70 sec                                               | 2.72 sec: 1.01x slower                                                  |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.81 sec: 1.01x slower                                                  |
| deepcopy                 | 355 us                                                 | 358 us: 1.01x slower                                                    |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                    |
| deepcopy_reduce          | 3.14 us                                                | 3.18 us: 1.01x slower                                                   |
| python_startup           | 9.47 ms                                                | 9.59 ms: 1.01x slower                                                   |
| dulwich_log              | 67.9 ms                                                | 69.0 ms: 1.02x slower                                                   |
| sqlglot_optimize         | 53.3 ms                                                | 54.2 ms: 1.02x slower                                                   |
| pickle_dict              | 31.6 us                                                | 32.2 us: 1.02x slower                                                   |
| json                     | 4.77 ms                                                | 4.86 ms: 1.02x slower                                                   |
| tomli_loads              | 2.22 sec                                               | 2.26 sec: 1.02x slower                                                  |
| bench_thread_pool        | 827 us                                                 | 844 us: 1.02x slower                                                    |
| pathlib                  | 18.5 ms                                                | 18.9 ms: 1.02x slower                                                   |
| regex_effbot             | 3.55 ms                                                | 3.63 ms: 1.02x slower                                                   |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                                   |
| python_startup_no_site   | 6.90 ms                                                | 7.06 ms: 1.02x slower                                                   |
| scimark_lu               | 114 ms                                                 | 117 ms: 1.02x slower                                                    |
| regex_compile            | 144 ms                                                 | 147 ms: 1.02x slower                                                    |
| float                    | 80.7 ms                                                | 82.9 ms: 1.03x slower                                                   |
| pprint_safe_repr         | 735 ms                                                 | 756 ms: 1.03x slower                                                    |
| spectral_norm            | 106 ms                                                 | 110 ms: 1.03x slower                                                    |
| pprint_pformat           | 1.50 sec                                               | 1.55 sec: 1.03x slower                                                  |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                  |
| mypy2                    | 344 ms                                                 | 357 ms: 1.04x slower                                                    |
| scimark_fft              | 358 ms                                                 | 374 ms: 1.04x slower                                                    |
| pickle_list              | 4.62 us                                                | 4.83 us: 1.05x slower                                                   |
| chaos                    | 63.5 ms                                                | 67.5 ms: 1.06x slower                                                   |
| async_generators         | 440 ms                                                 | 471 ms: 1.07x slower                                                    |
| pyflate                  | 450 ms                                                 | 482 ms: 1.07x slower                                                    |
| mdp                      | 2.57 sec                                               | 2.76 sec: 1.08x slower                                                  |
| mako                     | 10.7 ms                                                | 11.6 ms: 1.08x slower                                                   |
| meteor_contest           | 105 ms                                                 | 113 ms: 1.08x slower                                                    |
| pycparser                | 1.15 sec                                               | 1.24 sec: 1.08x slower                                                  |
| regex_dna                | 209 ms                                                 | 226 ms: 1.08x slower                                                    |
| unpickle_pure_python     | 218 us                                                 | 237 us: 1.09x slower                                                    |
| typing_runtime_protocols | 146 us                                                 | 158 us: 1.09x slower                                                    |
| deepcopy_memo            | 37.4 us                                                | 40.7 us: 1.09x slower                                                   |
| fannkuch                 | 387 ms                                                 | 426 ms: 1.10x slower                                                    |
| logging_silent           | 99.1 ns                                                | 110 ns: 1.11x slower                                                    |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.25 ms: 1.11x slower                                                   |
| go                       | 136 ms                                                 | 152 ms: 1.12x slower                                                    |
| regex_v8                 | 22.3 ms                                                | 25.2 ms: 1.13x slower                                                   |
| richards_super           | 49.0 ms                                                | 55.3 ms: 1.13x slower                                                   |
| unpack_sequence          | 44.8 ns                                                | 51.5 ns: 1.15x slower                                                   |
| richards                 | 43.2 ms                                                | 49.6 ms: 1.15x slower                                                   |
| nbody                    | 88.8 ms                                                | 103 ms: 1.16x slower                                                    |
| nqueens                  | 81.1 ms                                                | 94.9 ms: 1.17x slower                                                   |
| hexiom                   | 6.12 ms                                                | 7.29 ms: 1.19x slower                                                   |
| telco                    | 6.87 ms                                                | 8.35 ms: 1.22x slower                                                   |
| comprehensions           | 20.4 us                                                | 25.1 us: 1.23x slower                                                   |
| dask                     | 365 ms                                                 | 535 ms: 1.47x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                            |

Benchmark hidden because not significant (8): async_tree_cpu_io_mixed, sqlglot_normalize, unpickle_list, async_tree_memoization, bench_mp_pool, sqlite_synth, scimark_sor, json_loads
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
