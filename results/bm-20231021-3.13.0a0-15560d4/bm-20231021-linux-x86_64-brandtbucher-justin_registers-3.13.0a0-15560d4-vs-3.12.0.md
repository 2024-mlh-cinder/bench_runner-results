
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 15560d4
- commit date: 2023-10-21
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.74 sec: 1.01x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                    |
| float          | 80.7 ms                                                | 86.8 ms: 1.08x slower                                                   |
| nbody          | 88.8 ms                                                | 100.0 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                  | 1.07x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.65 ms: 1.03x slower                                                   |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                                    |
| regex_compile  | 144 ms                                                 | 151 ms: 1.05x slower                                                    |
| regex_v8       | 22.3 ms                                                | 25.8 ms: 1.15x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.14 sec: 1.03x faster                                                  |
| pickle_pure_python   | 309 us                                                 | 308 us: 1.00x faster                                                    |
| unpickle_list        | 4.95 us                                                | 5.00 us: 1.01x slower                                                   |
| xml_etree_generate   | 84.8 ms                                                | 87.0 ms: 1.03x slower                                                   |
| unpickle             | 15.0 us                                                | 15.4 us: 1.03x slower                                                   |
| xml_etree_process    | 58.6 ms                                                | 60.2 ms: 1.03x slower                                                   |
| xml_etree_parse      | 154 ms                                                 | 158 ms: 1.03x slower                                                    |
| xml_etree_iterparse  | 104 ms                                                 | 109 ms: 1.05x slower                                                    |
| unpickle_pure_python | 218 us                                                 | 234 us: 1.07x slower                                                    |
| json_dumps           | 9.85 ms                                                | 10.6 ms: 1.08x slower                                                   |
| pickle_list          | 4.62 us                                                | 5.02 us: 1.09x slower                                                   |
| pickle_dict          | 31.6 us                                                | 34.5 us: 1.09x slower                                                   |
| pickle               | 10.6 us                                                | 11.6 us: 1.09x slower                                                   |
| json_loads           | 25.2 us                                                | 28.3 us: 1.12x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.05x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.93 ms: 1.01x slower                                                   |
| python_startup         | 9.47 ms                                                | 10.2 ms: 1.07x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.04x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 12.1 ms: 1.13x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 490 ms: 1.07x faster                                                    |
| generators               | 31.1 ms                                                | 29.4 ms: 1.06x faster                                                   |
| async_tree_none          | 469 ms                                                 | 450 ms: 1.04x faster                                                    |
| create_gc_cycles         | 1.52 ms                                                | 1.46 ms: 1.04x faster                                                   |
| tomli_loads              | 2.22 sec                                               | 2.14 sec: 1.03x faster                                                  |
| coverage                 | 94.2 ms                                                | 91.2 ms: 1.03x faster                                                   |
| crypto_pyaes             | 77.2 ms                                                | 76.2 ms: 1.01x faster                                                   |
| gc_traversal             | 3.84 ms                                                | 3.82 ms: 1.01x faster                                                   |
| pickle_pure_python       | 309 us                                                 | 308 us: 1.00x faster                                                    |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                                  |
| scimark_fft              | 358 ms                                                 | 360 ms: 1.00x slower                                                    |
| python_startup_no_site   | 6.90 ms                                                | 6.93 ms: 1.01x slower                                                   |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.01x slower                                                    |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                    |
| unpickle_list            | 4.95 us                                                | 5.00 us: 1.01x slower                                                   |
| async_tree_memoization   | 573 ms                                                 | 579 ms: 1.01x slower                                                    |
| docutils                 | 2.70 sec                                               | 2.74 sec: 1.01x slower                                                  |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 724 ms: 1.01x slower                                                    |
| deepcopy                 | 355 us                                                 | 362 us: 1.02x slower                                                    |
| deepcopy_reduce          | 3.14 us                                                | 3.19 us: 1.02x slower                                                   |
| scimark_sor              | 125 ms                                                 | 127 ms: 1.02x slower                                                    |
| bench_thread_pool        | 827 us                                                 | 843 us: 1.02x slower                                                    |
| raytrace                 | 294 ms                                                 | 301 ms: 1.02x slower                                                    |
| sqlite_synth             | 2.76 us                                                | 2.83 us: 1.03x slower                                                   |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.03x slower                                                   |
| xml_etree_generate       | 84.8 ms                                                | 87.0 ms: 1.03x slower                                                   |
| sqlglot_optimize         | 53.3 ms                                                | 54.7 ms: 1.03x slower                                                   |
| unpickle                 | 15.0 us                                                | 15.4 us: 1.03x slower                                                   |
| dulwich_log              | 67.9 ms                                                | 69.8 ms: 1.03x slower                                                   |
| xml_etree_process        | 58.6 ms                                                | 60.2 ms: 1.03x slower                                                   |
| regex_effbot             | 3.55 ms                                                | 3.65 ms: 1.03x slower                                                   |
| xml_etree_parse          | 154 ms                                                 | 158 ms: 1.03x slower                                                    |
| scimark_lu               | 114 ms                                                 | 118 ms: 1.04x slower                                                    |
| regex_dna                | 209 ms                                                 | 217 ms: 1.04x slower                                                    |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                  |
| scimark_monte_carlo      | 71.0 ms                                                | 74.1 ms: 1.04x slower                                                   |
| regex_compile            | 144 ms                                                 | 151 ms: 1.05x slower                                                    |
| mypy2                    | 344 ms                                                 | 361 ms: 1.05x slower                                                    |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.00 ms: 1.05x slower                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 109 ms: 1.05x slower                                                    |
| pycparser                | 1.15 sec                                               | 1.22 sec: 1.06x slower                                                  |
| meteor_contest           | 105 ms                                                 | 112 ms: 1.07x slower                                                    |
| unpickle_pure_python     | 218 us                                                 | 234 us: 1.07x slower                                                    |
| python_startup           | 9.47 ms                                                | 10.2 ms: 1.07x slower                                                   |
| float                    | 80.7 ms                                                | 86.8 ms: 1.08x slower                                                   |
| json_dumps               | 9.85 ms                                                | 10.6 ms: 1.08x slower                                                   |
| typing_runtime_protocols | 146 us                                                 | 158 us: 1.08x slower                                                    |
| async_generators         | 440 ms                                                 | 476 ms: 1.08x slower                                                    |
| deltablue                | 3.52 ms                                                | 3.81 ms: 1.08x slower                                                   |
| logging_silent           | 99.1 ns                                                | 107 ns: 1.08x slower                                                    |
| pickle_list              | 4.62 us                                                | 5.02 us: 1.09x slower                                                   |
| json                     | 4.77 ms                                                | 5.20 ms: 1.09x slower                                                   |
| pickle_dict              | 31.6 us                                                | 34.5 us: 1.09x slower                                                   |
| deepcopy_memo            | 37.4 us                                                | 40.8 us: 1.09x slower                                                   |
| pickle                   | 10.6 us                                                | 11.6 us: 1.09x slower                                                   |
| fannkuch                 | 387 ms                                                 | 423 ms: 1.09x slower                                                    |
| mdp                      | 2.57 sec                                               | 2.81 sec: 1.09x slower                                                  |
| spectral_norm            | 106 ms                                                 | 118 ms: 1.11x slower                                                    |
| richards                 | 43.2 ms                                                | 47.9 ms: 1.11x slower                                                   |
| richards_super           | 49.0 ms                                                | 54.5 ms: 1.11x slower                                                   |
| json_loads               | 25.2 us                                                | 28.3 us: 1.12x slower                                                   |
| nbody                    | 88.8 ms                                                | 100.0 ms: 1.13x slower                                                  |
| mako                     | 10.7 ms                                                | 12.1 ms: 1.13x slower                                                   |
| go                       | 136 ms                                                 | 153 ms: 1.13x slower                                                    |
| pprint_safe_repr         | 735 ms                                                 | 835 ms: 1.14x slower                                                    |
| nqueens                  | 81.1 ms                                                | 92.6 ms: 1.14x slower                                                   |
| pyflate                  | 450 ms                                                 | 517 ms: 1.15x slower                                                    |
| regex_v8                 | 22.3 ms                                                | 25.8 ms: 1.15x slower                                                   |
| pprint_pformat           | 1.50 sec                                               | 1.73 sec: 1.15x slower                                                  |
| chaos                    | 63.5 ms                                                | 73.7 ms: 1.16x slower                                                   |
| unpack_sequence          | 44.8 ns                                                | 53.6 ns: 1.19x slower                                                   |
| telco                    | 6.87 ms                                                | 8.52 ms: 1.24x slower                                                   |
| comprehensions           | 20.4 us                                                | 25.9 us: 1.27x slower                                                   |
| hexiom                   | 6.12 ms                                                | 8.25 ms: 1.35x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.06x slower                                                            |

Benchmark hidden because not significant (7): logging_format, sqlglot_parse, logging_simple, bench_mp_pool, sqlglot_transpile, tornado_http, coroutines
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
