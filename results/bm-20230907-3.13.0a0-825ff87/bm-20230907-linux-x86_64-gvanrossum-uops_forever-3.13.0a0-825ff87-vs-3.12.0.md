
# Results vs. 3.12.0

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: 825ff87
- commit date: 2023-09-07
- overall geometric mean: 1.04x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.72 sec: 1.00x slower                                            |
| tornado_http   | 99.6 ms                                                | 97.8 ms: 1.02x faster                                             |
| Geometric mean | (ref)                                                  | 1.01x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                              |
| float          | 80.7 ms                                                | 84.9 ms: 1.05x slower                                             |
| nbody          | 88.8 ms                                                | 106 ms: 1.19x slower                                              |
| Geometric mean | (ref)                                                  | 1.08x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 220 ms: 1.06x slower                                              |
| regex_compile  | 144 ms                                                 | 152 ms: 1.06x slower                                              |
| regex_effbot   | 3.55 ms                                                | 3.82 ms: 1.08x slower                                             |
| regex_v8       | 22.3 ms                                                | 25.0 ms: 1.12x slower                                             |
| Geometric mean | (ref)                                                  | 1.08x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 13.8 us: 1.08x faster                                             |
| xml_etree_process    | 58.6 ms                                                | 56.9 ms: 1.03x faster                                             |
| pickle_pure_python   | 309 us                                                 | 303 us: 1.02x faster                                              |
| xml_etree_generate   | 84.8 ms                                                | 83.3 ms: 1.02x faster                                             |
| unpickle_list        | 4.95 us                                                | 4.87 us: 1.02x faster                                             |
| pickle_dict          | 31.6 us                                                | 31.3 us: 1.01x faster                                             |
| pickle_list          | 4.62 us                                                | 4.59 us: 1.00x faster                                             |
| json_dumps           | 9.85 ms                                                | 9.90 ms: 1.01x slower                                             |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                             |
| tomli_loads          | 2.22 sec                                               | 2.39 sec: 1.08x slower                                            |
| unpickle_pure_python | 218 us                                                 | 238 us: 1.09x slower                                              |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                      |

Benchmark hidden because not significant (3): xml_etree_iterparse, xml_etree_parse, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.54 ms: 1.01x slower                                             |
| python_startup_no_site | 6.90 ms                                                | 7.01 ms: 1.02x slower                                             |
| Geometric mean         | (ref)                                                  | 1.01x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.9 ms: 1.11x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| unpickle                 | 15.0 us                                                | 13.8 us: 1.08x faster                                             |
| asyncio_tcp              | 526 ms                                                 | 492 ms: 1.07x faster                                              |
| crypto_pyaes             | 77.2 ms                                                | 72.4 ms: 1.07x faster                                             |
| coverage                 | 94.2 ms                                                | 89.2 ms: 1.06x faster                                             |
| async_tree_none          | 469 ms                                                 | 447 ms: 1.05x faster                                              |
| raytrace                 | 294 ms                                                 | 281 ms: 1.05x faster                                              |
| generators               | 31.1 ms                                                | 29.8 ms: 1.04x faster                                             |
| scimark_monte_carlo      | 71.0 ms                                                | 68.7 ms: 1.03x faster                                             |
| xml_etree_process        | 58.6 ms                                                | 56.9 ms: 1.03x faster                                             |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.03x faster                                             |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.02x faster                                             |
| pickle_pure_python       | 309 us                                                 | 303 us: 1.02x faster                                              |
| xml_etree_generate       | 84.8 ms                                                | 83.3 ms: 1.02x faster                                             |
| tornado_http             | 99.6 ms                                                | 97.8 ms: 1.02x faster                                             |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                              |
| unpickle_list            | 4.95 us                                                | 4.87 us: 1.02x faster                                             |
| logging_format           | 6.90 us                                                | 6.82 us: 1.01x faster                                             |
| logging_simple           | 6.18 us                                                | 6.10 us: 1.01x faster                                             |
| pickle_dict              | 31.6 us                                                | 31.3 us: 1.01x faster                                             |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                              |
| deltablue                | 3.52 ms                                                | 3.49 ms: 1.01x faster                                             |
| create_gc_cycles         | 1.52 ms                                                | 1.51 ms: 1.01x faster                                             |
| pickle_list              | 4.62 us                                                | 4.59 us: 1.00x faster                                             |
| gc_traversal             | 3.84 ms                                                | 3.83 ms: 1.00x faster                                             |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                            |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                              |
| sqlglot_optimize         | 53.3 ms                                                | 53.6 ms: 1.00x slower                                             |
| docutils                 | 2.70 sec                                               | 2.72 sec: 1.00x slower                                            |
| json_dumps               | 9.85 ms                                                | 9.90 ms: 1.01x slower                                             |
| dulwich_log              | 67.9 ms                                                | 68.4 ms: 1.01x slower                                             |
| python_startup           | 9.47 ms                                                | 9.54 ms: 1.01x slower                                             |
| coroutines               | 22.4 ms                                                | 22.7 ms: 1.01x slower                                             |
| async_tree_memoization   | 573 ms                                                 | 580 ms: 1.01x slower                                              |
| deepcopy                 | 355 us                                                 | 360 us: 1.01x slower                                              |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                             |
| python_startup_no_site   | 6.90 ms                                                | 7.01 ms: 1.02x slower                                             |
| mypy2                    | 344 ms                                                 | 350 ms: 1.02x slower                                              |
| pprint_safe_repr         | 735 ms                                                 | 749 ms: 1.02x slower                                              |
| pathlib                  | 18.5 ms                                                | 18.9 ms: 1.02x slower                                             |
| pprint_pformat           | 1.50 sec                                               | 1.53 sec: 1.02x slower                                            |
| bench_thread_pool        | 827 us                                                 | 847 us: 1.02x slower                                              |
| spectral_norm            | 106 ms                                                 | 109 ms: 1.03x slower                                              |
| logging_silent           | 99.1 ns                                                | 102 ns: 1.03x slower                                              |
| deepcopy_reduce          | 3.14 us                                                | 3.25 us: 1.04x slower                                             |
| scimark_lu               | 114 ms                                                 | 118 ms: 1.04x slower                                              |
| typing_runtime_protocols | 146 us                                                 | 153 us: 1.05x slower                                              |
| async_generators         | 440 ms                                                 | 461 ms: 1.05x slower                                              |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.05x slower                                            |
| float                    | 80.7 ms                                                | 84.9 ms: 1.05x slower                                             |
| regex_dna                | 209 ms                                                 | 220 ms: 1.06x slower                                              |
| regex_compile            | 144 ms                                                 | 152 ms: 1.06x slower                                              |
| chaos                    | 63.5 ms                                                | 68.4 ms: 1.08x slower                                             |
| regex_effbot             | 3.55 ms                                                | 3.82 ms: 1.08x slower                                             |
| tomli_loads              | 2.22 sec                                               | 2.39 sec: 1.08x slower                                            |
| json                     | 4.77 ms                                                | 5.15 ms: 1.08x slower                                             |
| pycparser                | 1.15 sec                                               | 1.24 sec: 1.08x slower                                            |
| scimark_fft              | 358 ms                                                 | 388 ms: 1.08x slower                                              |
| pyflate                  | 450 ms                                                 | 491 ms: 1.09x slower                                              |
| unpickle_pure_python     | 218 us                                                 | 238 us: 1.09x slower                                              |
| go                       | 136 ms                                                 | 149 ms: 1.10x slower                                              |
| meteor_contest           | 105 ms                                                 | 115 ms: 1.10x slower                                              |
| deepcopy_memo            | 37.4 us                                                | 41.4 us: 1.11x slower                                             |
| mdp                      | 2.57 sec                                               | 2.84 sec: 1.11x slower                                            |
| mako                     | 10.7 ms                                                | 11.9 ms: 1.11x slower                                             |
| regex_v8                 | 22.3 ms                                                | 25.0 ms: 1.12x slower                                             |
| richards_super           | 49.0 ms                                                | 55.4 ms: 1.13x slower                                             |
| fannkuch                 | 387 ms                                                 | 444 ms: 1.15x slower                                              |
| richards                 | 43.2 ms                                                | 50.0 ms: 1.16x slower                                             |
| nbody                    | 88.8 ms                                                | 106 ms: 1.19x slower                                              |
| nqueens                  | 81.1 ms                                                | 96.7 ms: 1.19x slower                                             |
| telco                    | 6.87 ms                                                | 8.25 ms: 1.20x slower                                             |
| unpack_sequence          | 44.8 ns                                                | 55.0 ns: 1.23x slower                                             |
| comprehensions           | 20.4 us                                                | 25.2 us: 1.23x slower                                             |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.89 ms: 1.24x slower                                             |
| hexiom                   | 6.12 ms                                                | 7.68 ms: 1.25x slower                                             |
| dask                     | 365 ms                                                 | 534 ms: 1.46x slower                                              |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                      |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed, xml_etree_iterparse, xml_etree_parse, json_loads, bench_mp_pool, sqlite_synth
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
