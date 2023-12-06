
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 0441b8d
- commit date: 2023-09-15
- overall geometric mean: 1.03x slower
- HPT reliability: 99.97%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| tornado_http   | 99.6 ms                                                | 97.9 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                                            |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.02x slower                                                    |
| float          | 80.7 ms                                                | 83.6 ms: 1.04x slower                                                   |
| nbody          | 88.8 ms                                                | 122 ms: 1.37x slower                                                    |
| Geometric mean | (ref)                                                  | 1.13x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.58 ms: 1.01x slower                                                   |
| regex_dna      | 209 ms                                                 | 213 ms: 1.02x slower                                                    |
| regex_compile  | 144 ms                                                 | 148 ms: 1.03x slower                                                    |
| regex_v8       | 22.3 ms                                                | 24.1 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 301 us: 1.03x faster                                                    |
| tomli_loads          | 2.22 sec                                               | 2.16 sec: 1.02x faster                                                  |
| unpickle             | 15.0 us                                                | 14.7 us: 1.02x faster                                                   |
| xml_etree_process    | 58.6 ms                                                | 57.9 ms: 1.01x faster                                                   |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                                   |
| pickle_list          | 4.62 us                                                | 4.59 us: 1.01x faster                                                   |
| pickle_dict          | 31.6 us                                                | 31.9 us: 1.01x slower                                                   |
| unpickle_list        | 4.95 us                                                | 5.01 us: 1.01x slower                                                   |
| unpickle_pure_python | 218 us                                                 | 236 us: 1.08x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                            |

Benchmark hidden because not significant (5): json_dumps, xml_etree_iterparse, xml_etree_generate, json_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.92 ms: 1.00x slower                                                   |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.7 ms: 1.09x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| generators               | 31.1 ms                                                | 28.2 ms: 1.10x faster                                                   |
| coverage                 | 94.2 ms                                                | 87.3 ms: 1.08x faster                                                   |
| asyncio_tcp              | 526 ms                                                 | 488 ms: 1.08x faster                                                    |
| raytrace                 | 294 ms                                                 | 276 ms: 1.07x faster                                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 67.6 ms: 1.05x faster                                                   |
| async_tree_none          | 469 ms                                                 | 451 ms: 1.04x faster                                                    |
| crypto_pyaes             | 77.2 ms                                                | 74.3 ms: 1.04x faster                                                   |
| pickle_pure_python       | 309 us                                                 | 301 us: 1.03x faster                                                    |
| tomli_loads              | 2.22 sec                                               | 2.16 sec: 1.02x faster                                                  |
| logging_format           | 6.90 us                                                | 6.75 us: 1.02x faster                                                   |
| coroutines               | 22.4 ms                                                | 22.0 ms: 1.02x faster                                                   |
| unpickle                 | 15.0 us                                                | 14.7 us: 1.02x faster                                                   |
| sqlglot_parse            | 1.32 ms                                                | 1.30 ms: 1.02x faster                                                   |
| tornado_http             | 99.6 ms                                                | 97.9 ms: 1.02x faster                                                   |
| deltablue                | 3.52 ms                                                | 3.46 ms: 1.02x faster                                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.62 ms: 1.01x faster                                                   |
| logging_simple           | 6.18 us                                                | 6.09 us: 1.01x faster                                                   |
| xml_etree_process        | 58.6 ms                                                | 57.9 ms: 1.01x faster                                                   |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                                   |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                                    |
| pickle_list              | 4.62 us                                                | 4.59 us: 1.01x faster                                                   |
| python_startup_no_site   | 6.90 ms                                                | 6.92 ms: 1.00x slower                                                   |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.01x slower                                                  |
| bench_thread_pool        | 827 us                                                 | 833 us: 1.01x slower                                                    |
| regex_effbot             | 3.55 ms                                                | 3.58 ms: 1.01x slower                                                   |
| pickle_dict              | 31.6 us                                                | 31.9 us: 1.01x slower                                                   |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.01x slower                                                  |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                   |
| sqlglot_optimize         | 53.3 ms                                                | 53.9 ms: 1.01x slower                                                   |
| unpickle_list            | 4.95 us                                                | 5.01 us: 1.01x slower                                                   |
| deepcopy_reduce          | 3.14 us                                                | 3.18 us: 1.01x slower                                                   |
| pidigits                 | 187 ms                                                 | 189 ms: 1.02x slower                                                    |
| sqlite_synth             | 2.76 us                                                | 2.80 us: 1.02x slower                                                   |
| regex_dna                | 209 ms                                                 | 213 ms: 1.02x slower                                                    |
| dulwich_log              | 67.9 ms                                                | 69.5 ms: 1.02x slower                                                   |
| regex_compile            | 144 ms                                                 | 148 ms: 1.03x slower                                                    |
| pycparser                | 1.15 sec                                               | 1.18 sec: 1.03x slower                                                  |
| json                     | 4.77 ms                                                | 4.92 ms: 1.03x slower                                                   |
| logging_silent           | 99.1 ns                                                | 102 ns: 1.03x slower                                                    |
| mypy2                    | 344 ms                                                 | 355 ms: 1.03x slower                                                    |
| float                    | 80.7 ms                                                | 83.6 ms: 1.04x slower                                                   |
| spectral_norm            | 106 ms                                                 | 111 ms: 1.04x slower                                                    |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.05x slower                                                  |
| pyflate                  | 450 ms                                                 | 475 ms: 1.05x slower                                                    |
| async_generators         | 440 ms                                                 | 465 ms: 1.06x slower                                                    |
| meteor_contest           | 105 ms                                                 | 111 ms: 1.06x slower                                                    |
| scimark_fft              | 358 ms                                                 | 381 ms: 1.06x slower                                                    |
| deepcopy_memo            | 37.4 us                                                | 39.9 us: 1.07x slower                                                   |
| typing_runtime_protocols | 146 us                                                 | 156 us: 1.07x slower                                                    |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                   |
| regex_v8                 | 22.3 ms                                                | 24.1 ms: 1.08x slower                                                   |
| unpickle_pure_python     | 218 us                                                 | 236 us: 1.08x slower                                                    |
| mdp                      | 2.57 sec                                               | 2.79 sec: 1.09x slower                                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.16 ms: 1.09x slower                                                   |
| mako                     | 10.7 ms                                                | 11.7 ms: 1.09x slower                                                   |
| go                       | 136 ms                                                 | 149 ms: 1.10x slower                                                    |
| fannkuch                 | 387 ms                                                 | 427 ms: 1.10x slower                                                    |
| unpack_sequence          | 44.8 ns                                                | 49.6 ns: 1.11x slower                                                   |
| richards_super           | 49.0 ms                                                | 54.8 ms: 1.12x slower                                                   |
| richards                 | 43.2 ms                                                | 48.4 ms: 1.12x slower                                                   |
| chaos                    | 63.5 ms                                                | 72.0 ms: 1.13x slower                                                   |
| telco                    | 6.87 ms                                                | 8.15 ms: 1.19x slower                                                   |
| hexiom                   | 6.12 ms                                                | 7.34 ms: 1.20x slower                                                   |
| nqueens                  | 81.1 ms                                                | 98.4 ms: 1.21x slower                                                   |
| comprehensions           | 20.4 us                                                | 24.9 us: 1.22x slower                                                   |
| nbody                    | 88.8 ms                                                | 122 ms: 1.37x slower                                                    |
| dask                     | 365 ms                                                 | 536 ms: 1.47x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.03x slower                                                            |

Benchmark hidden because not significant (14): pprint_safe_repr, json_dumps, deepcopy, xml_etree_iterparse, xml_etree_generate, bench_mp_pool, scimark_lu, docutils, create_gc_cycles, sqlglot_normalize, async_tree_cpu_io_mixed, json_loads, xml_etree_parse, async_tree_memoization
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.97% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
