
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 1778268
- commit date: 2023-09-25
- overall geometric mean: 1.03x slower
- HPT reliability: 99.77%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.68 sec: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 195 ms: 1.05x slower                                                    |
| float          | 80.7 ms                                                | 86.8 ms: 1.07x slower                                                   |
| nbody          | 88.8 ms                                                | 103 ms: 1.16x slower                                                    |
| Geometric mean | (ref)                                                  | 1.09x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.40 ms: 1.04x faster                                                   |
| regex_dna      | 209 ms                                                 | 205 ms: 1.02x faster                                                    |
| regex_compile  | 144 ms                                                 | 149 ms: 1.04x slower                                                    |
| regex_v8       | 22.3 ms                                                | 23.4 ms: 1.05x slower                                                   |
| Geometric mean | (ref)                                                  | 1.00x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                  |
| unpickle_list        | 4.95 us                                                | 4.80 us: 1.03x faster                                                   |
| xml_etree_process    | 58.6 ms                                                | 57.4 ms: 1.02x faster                                                   |
| pickle_pure_python   | 309 us                                                 | 303 us: 1.02x faster                                                    |
| xml_etree_generate   | 84.8 ms                                                | 83.2 ms: 1.02x faster                                                   |
| xml_etree_parse      | 154 ms                                                 | 151 ms: 1.02x faster                                                    |
| pickle_dict          | 31.6 us                                                | 31.1 us: 1.02x faster                                                   |
| json_loads           | 25.2 us                                                | 25.0 us: 1.01x faster                                                   |
| pickle_list          | 4.62 us                                                | 4.72 us: 1.02x slower                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 107 ms: 1.03x slower                                                    |
| unpickle_pure_python | 218 us                                                 | 233 us: 1.07x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                            |

Benchmark hidden because not significant (3): pickle, json_dumps, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.88 ms: 1.00x faster                                                   |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.5 ms: 1.07x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230925-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-1778268 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 86.2 ms: 1.09x faster                                                   |
| generators               | 31.1 ms                                                | 28.9 ms: 1.07x faster                                                   |
| crypto_pyaes             | 77.2 ms                                                | 73.0 ms: 1.06x faster                                                   |
| asyncio_tcp              | 526 ms                                                 | 502 ms: 1.05x faster                                                    |
| regex_effbot             | 3.55 ms                                                | 3.40 ms: 1.04x faster                                                   |
| async_tree_none          | 469 ms                                                 | 451 ms: 1.04x faster                                                    |
| logging_format           | 6.90 us                                                | 6.67 us: 1.03x faster                                                   |
| tomli_loads              | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                  |
| unpickle_list            | 4.95 us                                                | 4.80 us: 1.03x faster                                                   |
| logging_simple           | 6.18 us                                                | 6.01 us: 1.03x faster                                                   |
| coroutines               | 22.4 ms                                                | 22.0 ms: 1.02x faster                                                   |
| xml_etree_process        | 58.6 ms                                                | 57.4 ms: 1.02x faster                                                   |
| regex_dna                | 209 ms                                                 | 205 ms: 1.02x faster                                                    |
| pickle_pure_python       | 309 us                                                 | 303 us: 1.02x faster                                                    |
| xml_etree_generate       | 84.8 ms                                                | 83.2 ms: 1.02x faster                                                   |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.02x faster                                                    |
| pickle_dict              | 31.6 us                                                | 31.1 us: 1.02x faster                                                   |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.02x faster                                                    |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                                   |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                    |
| deepcopy                 | 355 us                                                 | 351 us: 1.01x faster                                                    |
| sqlglot_parse            | 1.32 ms                                                | 1.31 ms: 1.01x faster                                                   |
| json_loads               | 25.2 us                                                | 25.0 us: 1.01x faster                                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.63 ms: 1.01x faster                                                   |
| docutils                 | 2.70 sec                                               | 2.68 sec: 1.01x faster                                                  |
| python_startup_no_site   | 6.90 ms                                                | 6.88 ms: 1.00x faster                                                   |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                   |
| deepcopy_reduce          | 3.14 us                                                | 3.15 us: 1.00x slower                                                   |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                                  |
| sqlglot_optimize         | 53.3 ms                                                | 53.7 ms: 1.01x slower                                                   |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.81 sec: 1.01x slower                                                  |
| bench_thread_pool        | 827 us                                                 | 838 us: 1.01x slower                                                    |
| dulwich_log              | 67.9 ms                                                | 69.3 ms: 1.02x slower                                                   |
| pickle_list              | 4.62 us                                                | 4.72 us: 1.02x slower                                                   |
| mdp                      | 2.57 sec                                               | 2.62 sec: 1.02x slower                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 107 ms: 1.03x slower                                                    |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                  |
| spectral_norm            | 106 ms                                                 | 109 ms: 1.03x slower                                                    |
| deepcopy_memo            | 37.4 us                                                | 38.7 us: 1.03x slower                                                   |
| regex_compile            | 144 ms                                                 | 149 ms: 1.04x slower                                                    |
| mypy2                    | 344 ms                                                 | 358 ms: 1.04x slower                                                    |
| async_generators         | 440 ms                                                 | 458 ms: 1.04x slower                                                    |
| regex_v8                 | 22.3 ms                                                | 23.4 ms: 1.05x slower                                                   |
| pidigits                 | 187 ms                                                 | 195 ms: 1.05x slower                                                    |
| meteor_contest           | 105 ms                                                 | 110 ms: 1.05x slower                                                    |
| typing_runtime_protocols | 146 us                                                 | 153 us: 1.05x slower                                                    |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.02 ms: 1.06x slower                                                   |
| fannkuch                 | 387 ms                                                 | 410 ms: 1.06x slower                                                    |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                   |
| unpickle_pure_python     | 218 us                                                 | 233 us: 1.07x slower                                                    |
| deltablue                | 3.52 ms                                                | 3.76 ms: 1.07x slower                                                   |
| logging_silent           | 99.1 ns                                                | 106 ns: 1.07x slower                                                    |
| richards                 | 43.2 ms                                                | 46.3 ms: 1.07x slower                                                   |
| mako                     | 10.7 ms                                                | 11.5 ms: 1.07x slower                                                   |
| float                    | 80.7 ms                                                | 86.8 ms: 1.07x slower                                                   |
| richards_super           | 49.0 ms                                                | 52.7 ms: 1.08x slower                                                   |
| unpack_sequence          | 44.8 ns                                                | 49.0 ns: 1.09x slower                                                   |
| pyflate                  | 450 ms                                                 | 498 ms: 1.11x slower                                                    |
| go                       | 136 ms                                                 | 150 ms: 1.11x slower                                                    |
| pprint_safe_repr         | 735 ms                                                 | 834 ms: 1.13x slower                                                    |
| nqueens                  | 81.1 ms                                                | 92.4 ms: 1.14x slower                                                   |
| nbody                    | 88.8 ms                                                | 103 ms: 1.16x slower                                                    |
| chaos                    | 63.5 ms                                                | 73.5 ms: 1.16x slower                                                   |
| telco                    | 6.87 ms                                                | 8.03 ms: 1.17x slower                                                   |
| pprint_pformat           | 1.50 sec                                               | 1.75 sec: 1.17x slower                                                  |
| comprehensions           | 20.4 us                                                | 25.9 us: 1.27x slower                                                   |
| hexiom                   | 6.12 ms                                                | 8.53 ms: 1.39x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.03x slower                                                            |

Benchmark hidden because not significant (13): tornado_http, scimark_lu, scimark_monte_carlo, async_tree_memoization, bench_mp_pool, json, scimark_fft, raytrace, pickle, json_dumps, sqlite_synth, async_tree_cpu_io_mixed, unpickle
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.77% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
