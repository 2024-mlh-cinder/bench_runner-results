
# Results vs. 3.12.0

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: 1ff7ef4
- commit date: 2023-08-28
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.73 sec: 1.01x slower                                            |
| tornado_http   | 99.6 ms                                                | 98.5 ms: 1.01x faster                                             |
| Geometric mean | (ref)                                                  | 1.00x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.02x slower                                              |
| float          | 80.7 ms                                                | 84.1 ms: 1.04x slower                                             |
| nbody          | 88.8 ms                                                | 102 ms: 1.15x slower                                              |
| Geometric mean | (ref)                                                  | 1.07x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.47 ms: 1.02x faster                                             |
| regex_dna      | 209 ms                                                 | 216 ms: 1.04x slower                                              |
| regex_compile  | 144 ms                                                 | 150 ms: 1.04x slower                                              |
| regex_v8       | 22.3 ms                                                | 25.0 ms: 1.12x slower                                             |
| Geometric mean | (ref)                                                  | 1.04x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.3 us: 1.04x faster                                             |
| pickle_list          | 4.62 us                                                | 4.52 us: 1.02x faster                                             |
| xml_etree_parse      | 154 ms                                                 | 151 ms: 1.02x faster                                              |
| pickle_pure_python   | 309 us                                                 | 307 us: 1.01x faster                                              |
| pickle_dict          | 31.6 us                                                | 31.6 us: 1.00x faster                                             |
| xml_etree_process    | 58.6 ms                                                | 58.8 ms: 1.01x slower                                             |
| xml_etree_generate   | 84.8 ms                                                | 85.4 ms: 1.01x slower                                             |
| json_loads           | 25.2 us                                                | 25.4 us: 1.01x slower                                             |
| json_dumps           | 9.85 ms                                                | 9.93 ms: 1.01x slower                                             |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                             |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                              |
| unpickle_list        | 4.95 us                                                | 5.08 us: 1.03x slower                                             |
| tomli_loads          | 2.22 sec                                               | 2.36 sec: 1.06x slower                                            |
| unpickle_pure_python | 218 us                                                 | 236 us: 1.08x slower                                              |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.37 ms: 1.01x faster                                             |
| python_startup_no_site | 6.90 ms                                                | 6.86 ms: 1.01x faster                                             |
| Geometric mean         | (ref)                                                  | 1.01x faster                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.8 ms: 1.11x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-1ff7ef4 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 85.4 ms: 1.10x faster                                             |
| generators               | 31.1 ms                                                | 28.9 ms: 1.08x faster                                             |
| crypto_pyaes             | 77.2 ms                                                | 73.6 ms: 1.05x faster                                             |
| async_tree_none          | 469 ms                                                 | 449 ms: 1.05x faster                                              |
| unpickle                 | 15.0 us                                                | 14.3 us: 1.04x faster                                             |
| scimark_monte_carlo      | 71.0 ms                                                | 68.1 ms: 1.04x faster                                             |
| logging_format           | 6.90 us                                                | 6.64 us: 1.04x faster                                             |
| logging_simple           | 6.18 us                                                | 5.95 us: 1.04x faster                                             |
| asyncio_tcp              | 526 ms                                                 | 510 ms: 1.03x faster                                              |
| create_gc_cycles         | 1.52 ms                                                | 1.48 ms: 1.03x faster                                             |
| raytrace                 | 294 ms                                                 | 288 ms: 1.02x faster                                              |
| regex_effbot             | 3.55 ms                                                | 3.47 ms: 1.02x faster                                             |
| pickle_list              | 4.62 us                                                | 4.52 us: 1.02x faster                                             |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.02x faster                                              |
| python_startup           | 9.47 ms                                                | 9.37 ms: 1.01x faster                                             |
| tornado_http             | 99.6 ms                                                | 98.5 ms: 1.01x faster                                             |
| pickle_pure_python       | 309 us                                                 | 307 us: 1.01x faster                                              |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                             |
| scimark_sor              | 125 ms                                                 | 124 ms: 1.01x faster                                              |
| python_startup_no_site   | 6.90 ms                                                | 6.86 ms: 1.01x faster                                             |
| pickle_dict              | 31.6 us                                                | 31.6 us: 1.00x faster                                             |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                            |
| sqlglot_normalize        | 107 ms                                                 | 108 ms: 1.00x slower                                              |
| xml_etree_process        | 58.6 ms                                                | 58.8 ms: 1.01x slower                                             |
| xml_etree_generate       | 84.8 ms                                                | 85.4 ms: 1.01x slower                                             |
| json_loads               | 25.2 us                                                | 25.4 us: 1.01x slower                                             |
| json_dumps               | 9.85 ms                                                | 9.93 ms: 1.01x slower                                             |
| deepcopy                 | 355 us                                                 | 359 us: 1.01x slower                                              |
| docutils                 | 2.70 sec                                               | 2.73 sec: 1.01x slower                                            |
| dulwich_log              | 67.9 ms                                                | 68.7 ms: 1.01x slower                                             |
| scimark_lu               | 114 ms                                                 | 115 ms: 1.01x slower                                              |
| pprint_safe_repr         | 735 ms                                                 | 746 ms: 1.01x slower                                              |
| pidigits                 | 187 ms                                                 | 189 ms: 1.02x slower                                              |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                             |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                              |
| pprint_pformat           | 1.50 sec                                               | 1.53 sec: 1.02x slower                                            |
| typing_runtime_protocols | 146 us                                                 | 149 us: 1.02x slower                                              |
| deltablue                | 3.52 ms                                                | 3.59 ms: 1.02x slower                                             |
| json                     | 4.77 ms                                                | 4.88 ms: 1.02x slower                                             |
| mypy2                    | 344 ms                                                 | 352 ms: 1.02x slower                                              |
| deepcopy_reduce          | 3.14 us                                                | 3.22 us: 1.02x slower                                             |
| sqlglot_optimize         | 53.3 ms                                                | 54.7 ms: 1.03x slower                                             |
| unpickle_list            | 4.95 us                                                | 5.08 us: 1.03x slower                                             |
| coroutines               | 22.4 ms                                                | 23.1 ms: 1.03x slower                                             |
| pathlib                  | 18.5 ms                                                | 19.1 ms: 1.03x slower                                             |
| spectral_norm            | 106 ms                                                 | 109 ms: 1.03x slower                                              |
| pycparser                | 1.15 sec                                               | 1.19 sec: 1.04x slower                                            |
| regex_dna                | 209 ms                                                 | 216 ms: 1.04x slower                                              |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.04x slower                                            |
| bench_thread_pool        | 827 us                                                 | 859 us: 1.04x slower                                              |
| regex_compile            | 144 ms                                                 | 150 ms: 1.04x slower                                              |
| float                    | 80.7 ms                                                | 84.1 ms: 1.04x slower                                             |
| scimark_fft              | 358 ms                                                 | 375 ms: 1.04x slower                                              |
| chaos                    | 63.5 ms                                                | 67.2 ms: 1.06x slower                                             |
| tomli_loads              | 2.22 sec                                               | 2.36 sec: 1.06x slower                                            |
| logging_silent           | 99.1 ns                                                | 106 ns: 1.07x slower                                              |
| async_generators         | 440 ms                                                 | 473 ms: 1.07x slower                                              |
| deepcopy_memo            | 37.4 us                                                | 40.4 us: 1.08x slower                                             |
| unpickle_pure_python     | 218 us                                                 | 236 us: 1.08x slower                                              |
| unpack_sequence          | 44.8 ns                                                | 48.7 ns: 1.09x slower                                             |
| gc_traversal             | 3.84 ms                                                | 4.19 ms: 1.09x slower                                             |
| mdp                      | 2.57 sec                                               | 2.81 sec: 1.09x slower                                            |
| go                       | 136 ms                                                 | 150 ms: 1.10x slower                                              |
| mako                     | 10.7 ms                                                | 11.8 ms: 1.11x slower                                             |
| meteor_contest           | 105 ms                                                 | 116 ms: 1.11x slower                                              |
| regex_v8                 | 22.3 ms                                                | 25.0 ms: 1.12x slower                                             |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.37 ms: 1.13x slower                                             |
| fannkuch                 | 387 ms                                                 | 441 ms: 1.14x slower                                              |
| pyflate                  | 450 ms                                                 | 516 ms: 1.14x slower                                              |
| nbody                    | 88.8 ms                                                | 102 ms: 1.15x slower                                              |
| richards                 | 43.2 ms                                                | 49.8 ms: 1.15x slower                                             |
| richards_super           | 49.0 ms                                                | 56.5 ms: 1.15x slower                                             |
| nqueens                  | 81.1 ms                                                | 96.8 ms: 1.19x slower                                             |
| telco                    | 6.87 ms                                                | 8.23 ms: 1.20x slower                                             |
| comprehensions           | 20.4 us                                                | 25.1 us: 1.23x slower                                             |
| hexiom                   | 6.12 ms                                                | 7.57 ms: 1.24x slower                                             |
| dask                     | 365 ms                                                 | 536 ms: 1.47x slower                                              |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                      |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed, bench_mp_pool, sqlglot_parse, sqlglot_transpile, async_tree_memoization
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
