
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: d70e866
- commit date: 2023-09-25
- overall geometric mean: 1.01x slower
- HPT reliability: 95.75%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.66 sec: 1.02x faster                                                  |
| tornado_http   | 99.6 ms                                                | 96.9 ms: 1.03x faster                                                   |
| Geometric mean | (ref)                                                  | 1.02x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                    |
| float          | 80.7 ms                                                | 82.3 ms: 1.02x slower                                                   |
| nbody          | 88.8 ms                                                | 95.9 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 201 ms: 1.04x faster                                                    |
| regex_effbot   | 3.55 ms                                                | 3.45 ms: 1.03x faster                                                   |
| regex_v8       | 22.3 ms                                                | 23.2 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                                            |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.02 sec: 1.09x faster                                                  |
| pickle_pure_python   | 309 us                                                 | 297 us: 1.04x faster                                                    |
| pickle               | 10.6 us                                                | 10.2 us: 1.04x faster                                                   |
| xml_etree_process    | 58.6 ms                                                | 57.3 ms: 1.02x faster                                                   |
| xml_etree_generate   | 84.8 ms                                                | 83.3 ms: 1.02x faster                                                   |
| unpickle_list        | 4.95 us                                                | 4.88 us: 1.01x faster                                                   |
| pickle_dict          | 31.6 us                                                | 31.2 us: 1.01x faster                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                    |
| json_dumps           | 9.85 ms                                                | 9.91 ms: 1.01x slower                                                   |
| pickle_list          | 4.62 us                                                | 4.66 us: 1.01x slower                                                   |
| unpickle_pure_python | 218 us                                                 | 227 us: 1.04x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                            |

Benchmark hidden because not significant (3): xml_etree_parse, json_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.90 ms: 1.00x slower                                                   |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.5 ms: 1.07x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-d70e866 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| generators               | 31.1 ms                                                | 28.2 ms: 1.10x faster                                                   |
| tomli_loads              | 2.22 sec                                               | 2.02 sec: 1.09x faster                                                  |
| coverage                 | 94.2 ms                                                | 86.3 ms: 1.09x faster                                                   |
| raytrace                 | 294 ms                                                 | 272 ms: 1.08x faster                                                    |
| crypto_pyaes             | 77.2 ms                                                | 71.5 ms: 1.08x faster                                                   |
| scimark_fft              | 358 ms                                                 | 334 ms: 1.07x faster                                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 67.0 ms: 1.06x faster                                                   |
| asyncio_tcp              | 526 ms                                                 | 498 ms: 1.05x faster                                                    |
| async_tree_none          | 469 ms                                                 | 448 ms: 1.05x faster                                                    |
| pickle_pure_python       | 309 us                                                 | 297 us: 1.04x faster                                                    |
| pickle                   | 10.6 us                                                | 10.2 us: 1.04x faster                                                   |
| regex_dna                | 209 ms                                                 | 201 ms: 1.04x faster                                                    |
| deltablue                | 3.52 ms                                                | 3.41 ms: 1.03x faster                                                   |
| regex_effbot             | 3.55 ms                                                | 3.45 ms: 1.03x faster                                                   |
| tornado_http             | 99.6 ms                                                | 96.9 ms: 1.03x faster                                                   |
| logging_format           | 6.90 us                                                | 6.73 us: 1.03x faster                                                   |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                                    |
| xml_etree_process        | 58.6 ms                                                | 57.3 ms: 1.02x faster                                                   |
| xml_etree_generate       | 84.8 ms                                                | 83.3 ms: 1.02x faster                                                   |
| docutils                 | 2.70 sec                                               | 2.66 sec: 1.02x faster                                                  |
| logging_simple           | 6.18 us                                                | 6.08 us: 1.02x faster                                                   |
| unpickle_list            | 4.95 us                                                | 4.88 us: 1.01x faster                                                   |
| sqlglot_parse            | 1.32 ms                                                | 1.30 ms: 1.01x faster                                                   |
| pickle_dict              | 31.6 us                                                | 31.2 us: 1.01x faster                                                   |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                    |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                    |
| coroutines               | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.63 ms: 1.01x faster                                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                                   |
| python_startup_no_site   | 6.90 ms                                                | 6.90 ms: 1.00x slower                                                   |
| sqlglot_optimize         | 53.3 ms                                                | 53.4 ms: 1.00x slower                                                   |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                    |
| pyflate                  | 450 ms                                                 | 453 ms: 1.01x slower                                                    |
| pprint_safe_repr         | 735 ms                                                 | 740 ms: 1.01x slower                                                    |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.81 sec: 1.01x slower                                                  |
| json_dumps               | 9.85 ms                                                | 9.91 ms: 1.01x slower                                                   |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.01x slower                                                  |
| pickle_list              | 4.62 us                                                | 4.66 us: 1.01x slower                                                   |
| dulwich_log              | 67.9 ms                                                | 68.6 ms: 1.01x slower                                                   |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                                   |
| bench_thread_pool        | 827 us                                                 | 838 us: 1.01x slower                                                    |
| spectral_norm            | 106 ms                                                 | 108 ms: 1.01x slower                                                    |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.02x slower                                                   |
| float                    | 80.7 ms                                                | 82.3 ms: 1.02x slower                                                   |
| mypy2                    | 344 ms                                                 | 352 ms: 1.02x slower                                                    |
| fannkuch                 | 387 ms                                                 | 396 ms: 1.02x slower                                                    |
| chaos                    | 63.5 ms                                                | 65.3 ms: 1.03x slower                                                   |
| json                     | 4.77 ms                                                | 4.91 ms: 1.03x slower                                                   |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                  |
| meteor_contest           | 105 ms                                                 | 108 ms: 1.03x slower                                                    |
| typing_runtime_protocols | 146 us                                                 | 151 us: 1.04x slower                                                    |
| regex_v8                 | 22.3 ms                                                | 23.2 ms: 1.04x slower                                                   |
| unpickle_pure_python     | 218 us                                                 | 227 us: 1.04x slower                                                    |
| pycparser                | 1.15 sec                                               | 1.20 sec: 1.04x slower                                                  |
| async_generators         | 440 ms                                                 | 460 ms: 1.04x slower                                                    |
| logging_silent           | 99.1 ns                                                | 104 ns: 1.05x slower                                                    |
| unpack_sequence          | 44.8 ns                                                | 47.2 ns: 1.05x slower                                                   |
| deepcopy_memo            | 37.4 us                                                | 39.5 us: 1.06x slower                                                   |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                   |
| gc_traversal             | 3.84 ms                                                | 4.11 ms: 1.07x slower                                                   |
| mako                     | 10.7 ms                                                | 11.5 ms: 1.07x slower                                                   |
| nbody                    | 88.8 ms                                                | 95.9 ms: 1.08x slower                                                   |
| go                       | 136 ms                                                 | 147 ms: 1.09x slower                                                    |
| nqueens                  | 81.1 ms                                                | 89.6 ms: 1.10x slower                                                   |
| richards                 | 43.2 ms                                                | 48.0 ms: 1.11x slower                                                   |
| richards_super           | 49.0 ms                                                | 54.4 ms: 1.11x slower                                                   |
| hexiom                   | 6.12 ms                                                | 6.95 ms: 1.14x slower                                                   |
| comprehensions           | 20.4 us                                                | 23.8 us: 1.16x slower                                                   |
| telco                    | 6.87 ms                                                | 8.08 ms: 1.18x slower                                                   |
| dask                     | 365 ms                                                 | 534 ms: 1.46x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (11): async_tree_memoization, xml_etree_parse, json_loads, deepcopy, regex_compile, async_tree_cpu_io_mixed, scimark_lu, bench_mp_pool, mdp, unpickle, scimark_sparse_mat_mult
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 95.75% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
