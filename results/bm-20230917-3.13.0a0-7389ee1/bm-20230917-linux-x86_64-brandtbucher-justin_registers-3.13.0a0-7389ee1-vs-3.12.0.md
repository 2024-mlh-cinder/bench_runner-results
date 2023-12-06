
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 7389ee1
- commit date: 2023-09-17
- overall geometric mean: 1.02x slower
- HPT reliability: 98.91%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.68 sec: 1.01x faster                                                  |
| tornado_http   | 99.6 ms                                                | 97.0 ms: 1.03x faster                                                   |
| Geometric mean | (ref)                                                  | 1.02x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                    |
| float          | 80.7 ms                                                | 82.8 ms: 1.03x slower                                                   |
| nbody          | 88.8 ms                                                | 93.3 ms: 1.05x slower                                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.46 ms: 1.02x faster                                                   |
| regex_v8       | 22.3 ms                                                | 23.7 ms: 1.06x slower                                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (2): regex_compile, regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.05 sec: 1.08x faster                                                  |
| pickle_pure_python   | 309 us                                                 | 299 us: 1.04x faster                                                    |
| unpickle_list        | 4.95 us                                                | 4.81 us: 1.03x faster                                                   |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                                   |
| xml_etree_process    | 58.6 ms                                                | 57.9 ms: 1.01x faster                                                   |
| xml_etree_generate   | 84.8 ms                                                | 84.0 ms: 1.01x faster                                                   |
| pickle_dict          | 31.6 us                                                | 31.9 us: 1.01x slower                                                   |
| json_dumps           | 9.85 ms                                                | 9.94 ms: 1.01x slower                                                   |
| unpickle             | 15.0 us                                                | 15.3 us: 1.02x slower                                                   |
| pickle_list          | 4.62 us                                                | 4.77 us: 1.03x slower                                                   |
| unpickle_pure_python | 218 us                                                 | 226 us: 1.04x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                            |

Benchmark hidden because not significant (3): xml_etree_iterparse, json_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.94 ms: 1.01x slower                                                   |
| python_startup         | 9.47 ms                                                | 10.2 ms: 1.07x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.4 ms: 1.07x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| generators               | 31.1 ms                                                | 28.3 ms: 1.10x faster                                                   |
| raytrace                 | 294 ms                                                 | 271 ms: 1.09x faster                                                    |
| tomli_loads              | 2.22 sec                                               | 2.05 sec: 1.08x faster                                                  |
| coverage                 | 94.2 ms                                                | 87.1 ms: 1.08x faster                                                   |
| scimark_fft              | 358 ms                                                 | 333 ms: 1.08x faster                                                    |
| crypto_pyaes             | 77.2 ms                                                | 72.1 ms: 1.07x faster                                                   |
| scimark_monte_carlo      | 71.0 ms                                                | 67.6 ms: 1.05x faster                                                   |
| async_tree_none          | 469 ms                                                 | 450 ms: 1.04x faster                                                    |
| asyncio_tcp              | 526 ms                                                 | 505 ms: 1.04x faster                                                    |
| pickle_pure_python       | 309 us                                                 | 299 us: 1.04x faster                                                    |
| deltablue                | 3.52 ms                                                | 3.40 ms: 1.03x faster                                                   |
| logging_format           | 6.90 us                                                | 6.68 us: 1.03x faster                                                   |
| unpickle_list            | 4.95 us                                                | 4.81 us: 1.03x faster                                                   |
| scimark_sor              | 125 ms                                                 | 121 ms: 1.03x faster                                                    |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.03x faster                                                   |
| tornado_http             | 99.6 ms                                                | 97.0 ms: 1.03x faster                                                   |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.63 ms: 1.02x faster                                                   |
| regex_effbot             | 3.55 ms                                                | 3.46 ms: 1.02x faster                                                   |
| logging_simple           | 6.18 us                                                | 6.05 us: 1.02x faster                                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                                   |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                                   |
| xml_etree_process        | 58.6 ms                                                | 57.9 ms: 1.01x faster                                                   |
| xml_etree_generate       | 84.8 ms                                                | 84.0 ms: 1.01x faster                                                   |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                    |
| docutils                 | 2.70 sec                                               | 2.68 sec: 1.01x faster                                                  |
| deepcopy                 | 355 us                                                 | 353 us: 1.01x faster                                                    |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                   |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                    |
| create_gc_cycles         | 1.52 ms                                                | 1.53 ms: 1.00x slower                                                   |
| python_startup_no_site   | 6.90 ms                                                | 6.94 ms: 1.01x slower                                                   |
| sqlglot_optimize         | 53.3 ms                                                | 53.6 ms: 1.01x slower                                                   |
| bench_thread_pool        | 827 us                                                 | 833 us: 1.01x slower                                                    |
| deepcopy_reduce          | 3.14 us                                                | 3.16 us: 1.01x slower                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.81 sec: 1.01x slower                                                  |
| pickle_dict              | 31.6 us                                                | 31.9 us: 1.01x slower                                                   |
| chaos                    | 63.5 ms                                                | 64.2 ms: 1.01x slower                                                   |
| json_dumps               | 9.85 ms                                                | 9.94 ms: 1.01x slower                                                   |
| dulwich_log              | 67.9 ms                                                | 68.7 ms: 1.01x slower                                                   |
| pyflate                  | 450 ms                                                 | 457 ms: 1.01x slower                                                    |
| json                     | 4.77 ms                                                | 4.85 ms: 1.02x slower                                                   |
| pathlib                  | 18.5 ms                                                | 18.9 ms: 1.02x slower                                                   |
| unpickle                 | 15.0 us                                                | 15.3 us: 1.02x slower                                                   |
| mypy2                    | 344 ms                                                 | 351 ms: 1.02x slower                                                    |
| float                    | 80.7 ms                                                | 82.8 ms: 1.03x slower                                                   |
| pprint_pformat           | 1.50 sec                                               | 1.54 sec: 1.03x slower                                                  |
| pprint_safe_repr         | 735 ms                                                 | 755 ms: 1.03x slower                                                    |
| meteor_contest           | 105 ms                                                 | 108 ms: 1.03x slower                                                    |
| pickle_list              | 4.62 us                                                | 4.77 us: 1.03x slower                                                   |
| fannkuch                 | 387 ms                                                 | 400 ms: 1.03x slower                                                    |
| spectral_norm            | 106 ms                                                 | 110 ms: 1.03x slower                                                    |
| unpickle_pure_python     | 218 us                                                 | 226 us: 1.04x slower                                                    |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                  |
| typing_runtime_protocols | 146 us                                                 | 152 us: 1.05x slower                                                    |
| pycparser                | 1.15 sec                                               | 1.20 sec: 1.05x slower                                                  |
| async_generators         | 440 ms                                                 | 462 ms: 1.05x slower                                                    |
| nbody                    | 88.8 ms                                                | 93.3 ms: 1.05x slower                                                   |
| deepcopy_memo            | 37.4 us                                                | 39.4 us: 1.05x slower                                                   |
| regex_v8                 | 22.3 ms                                                | 23.7 ms: 1.06x slower                                                   |
| mako                     | 10.7 ms                                                | 11.4 ms: 1.07x slower                                                   |
| logging_silent           | 99.1 ns                                                | 106 ns: 1.07x slower                                                    |
| python_startup           | 9.47 ms                                                | 10.2 ms: 1.07x slower                                                   |
| mdp                      | 2.57 sec                                               | 2.77 sec: 1.08x slower                                                  |
| go                       | 136 ms                                                 | 147 ms: 1.08x slower                                                    |
| nqueens                  | 81.1 ms                                                | 88.8 ms: 1.09x slower                                                   |
| richards                 | 43.2 ms                                                | 48.1 ms: 1.11x slower                                                   |
| richards_super           | 49.0 ms                                                | 55.4 ms: 1.13x slower                                                   |
| hexiom                   | 6.12 ms                                                | 6.96 ms: 1.14x slower                                                   |
| unpack_sequence          | 44.8 ns                                                | 51.5 ns: 1.15x slower                                                   |
| comprehensions           | 20.4 us                                                | 23.8 us: 1.16x slower                                                   |
| telco                    | 6.87 ms                                                | 8.25 ms: 1.20x slower                                                   |
| dask                     | 365 ms                                                 | 536 ms: 1.47x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                            |

Benchmark hidden because not significant (11): sqlite_synth, xml_etree_iterparse, scimark_lu, regex_compile, regex_dna, bench_mp_pool, coroutines, json_loads, async_tree_cpu_io_mixed, xml_etree_parse, async_tree_memoization
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.91% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
