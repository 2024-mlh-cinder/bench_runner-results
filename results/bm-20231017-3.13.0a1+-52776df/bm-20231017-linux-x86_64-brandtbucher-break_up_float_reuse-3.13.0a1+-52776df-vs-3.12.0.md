
# Results vs. 3.12.0

- fork: brandtbucher
- ref: break_up_float_reuse
- machine: linux-x86_64
- commit hash: 52776df
- commit date: 2023-10-17
- overall geometric mean: 1.02x slower
- HPT reliability: 99.29%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.64 sec: 1.02x faster                                                       |
| tornado_http   | 99.6 ms                                                | 95.9 ms: 1.04x faster                                                        |
| Geometric mean | (ref)                                                  | 1.03x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                         |
| float          | 80.7 ms                                                | 81.6 ms: 1.01x slower                                                        |
| nbody          | 88.8 ms                                                | 95.1 ms: 1.07x slower                                                        |
| Geometric mean | (ref)                                                  | 1.03x slower                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                         |
| regex_dna      | 209 ms                                                 | 214 ms: 1.03x slower                                                         |
| regex_effbot   | 3.55 ms                                                | 4.06 ms: 1.14x slower                                                        |
| regex_v8       | 22.3 ms                                                | 25.6 ms: 1.15x slower                                                        |
| Geometric mean | (ref)                                                  | 1.07x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.3 us: 1.04x faster                                                        |
| tomli_loads          | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                       |
| unpickle_list        | 4.95 us                                                | 5.00 us: 1.01x slower                                                        |
| xml_etree_generate   | 84.8 ms                                                | 85.8 ms: 1.01x slower                                                        |
| xml_etree_process    | 58.6 ms                                                | 59.5 ms: 1.02x slower                                                        |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                                         |
| unpickle_pure_python | 218 us                                                 | 225 us: 1.03x slower                                                         |
| xml_etree_parse      | 154 ms                                                 | 159 ms: 1.03x slower                                                         |
| json_dumps           | 9.85 ms                                                | 10.4 ms: 1.06x slower                                                        |
| pickle_list          | 4.62 us                                                | 4.97 us: 1.08x slower                                                        |
| pickle               | 10.6 us                                                | 11.7 us: 1.10x slower                                                        |
| json_loads           | 25.2 us                                                | 27.9 us: 1.11x slower                                                        |
| pickle_dict          | 31.6 us                                                | 35.6 us: 1.13x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                                 |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.82 ms: 1.01x faster                                                        |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                        |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 12.0 ms: 1.12x slower                                                        |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-break_up_float_reuse-3.13.0a1+-52776df |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 478 ms: 1.10x faster                                                         |
| logging_format           | 6.90 us                                                | 6.43 us: 1.07x faster                                                        |
| async_tree_none          | 469 ms                                                 | 438 ms: 1.07x faster                                                         |
| crypto_pyaes             | 77.2 ms                                                | 72.5 ms: 1.07x faster                                                        |
| deltablue                | 3.52 ms                                                | 3.32 ms: 1.06x faster                                                        |
| raytrace                 | 294 ms                                                 | 280 ms: 1.05x faster                                                         |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                         |
| unpack_sequence          | 44.8 ns                                                | 42.9 ns: 1.05x faster                                                        |
| create_gc_cycles         | 1.52 ms                                                | 1.46 ms: 1.05x faster                                                        |
| logging_simple           | 6.18 us                                                | 5.91 us: 1.05x faster                                                        |
| unpickle                 | 15.0 us                                                | 14.3 us: 1.04x faster                                                        |
| generators               | 31.1 ms                                                | 29.8 ms: 1.04x faster                                                        |
| tornado_http             | 99.6 ms                                                | 95.9 ms: 1.04x faster                                                        |
| scimark_monte_carlo      | 71.0 ms                                                | 68.6 ms: 1.04x faster                                                        |
| coverage                 | 94.2 ms                                                | 91.1 ms: 1.03x faster                                                        |
| tomli_loads              | 2.22 sec                                               | 2.16 sec: 1.03x faster                                                       |
| chaos                    | 63.5 ms                                                | 62.0 ms: 1.02x faster                                                        |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.02x faster                                                        |
| docutils                 | 2.70 sec                                               | 2.64 sec: 1.02x faster                                                       |
| bench_thread_pool        | 827 us                                                 | 811 us: 1.02x faster                                                         |
| async_tree_memoization   | 573 ms                                                 | 562 ms: 1.02x faster                                                         |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                                        |
| dulwich_log              | 67.9 ms                                                | 66.7 ms: 1.02x faster                                                        |
| python_startup_no_site   | 6.90 ms                                                | 6.82 ms: 1.01x faster                                                        |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                         |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                                                       |
| mypy2                    | 344 ms                                                 | 342 ms: 1.00x faster                                                         |
| deepcopy                 | 355 us                                                 | 357 us: 1.00x slower                                                         |
| sqlglot_optimize         | 53.3 ms                                                | 53.6 ms: 1.01x slower                                                        |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                         |
| mdp                      | 2.57 sec                                               | 2.58 sec: 1.01x slower                                                       |
| scimark_lu               | 114 ms                                                 | 115 ms: 1.01x slower                                                         |
| pprint_pformat           | 1.50 sec                                               | 1.52 sec: 1.01x slower                                                       |
| float                    | 80.7 ms                                                | 81.6 ms: 1.01x slower                                                        |
| coroutines               | 22.4 ms                                                | 22.7 ms: 1.01x slower                                                        |
| unpickle_list            | 4.95 us                                                | 5.00 us: 1.01x slower                                                        |
| xml_etree_generate       | 84.8 ms                                                | 85.8 ms: 1.01x slower                                                        |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.82 ms: 1.02x slower                                                        |
| xml_etree_process        | 58.6 ms                                                | 59.5 ms: 1.02x slower                                                        |
| pyflate                  | 450 ms                                                 | 459 ms: 1.02x slower                                                         |
| comprehensions           | 20.4 us                                                | 20.8 us: 1.02x slower                                                        |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                                         |
| async_tree_io            | 1.16 sec                                               | 1.18 sec: 1.02x slower                                                       |
| deepcopy_reduce          | 3.14 us                                                | 3.21 us: 1.02x slower                                                        |
| pprint_safe_repr         | 735 ms                                                 | 753 ms: 1.02x slower                                                         |
| regex_dna                | 209 ms                                                 | 214 ms: 1.03x slower                                                         |
| scimark_fft              | 358 ms                                                 | 369 ms: 1.03x slower                                                         |
| hexiom                   | 6.12 ms                                                | 6.31 ms: 1.03x slower                                                        |
| unpickle_pure_python     | 218 us                                                 | 225 us: 1.03x slower                                                         |
| sqlite_synth             | 2.76 us                                                | 2.85 us: 1.03x slower                                                        |
| xml_etree_parse          | 154 ms                                                 | 159 ms: 1.03x slower                                                         |
| pathlib                  | 18.5 ms                                                | 19.2 ms: 1.04x slower                                                        |
| meteor_contest           | 105 ms                                                 | 109 ms: 1.04x slower                                                         |
| deepcopy_memo            | 37.4 us                                                | 39.2 us: 1.05x slower                                                        |
| async_generators         | 440 ms                                                 | 462 ms: 1.05x slower                                                         |
| gc_traversal             | 3.84 ms                                                | 4.04 ms: 1.05x slower                                                        |
| pycparser                | 1.15 sec                                               | 1.21 sec: 1.05x slower                                                       |
| typing_runtime_protocols | 146 us                                                 | 154 us: 1.05x slower                                                         |
| json_dumps               | 9.85 ms                                                | 10.4 ms: 1.06x slower                                                        |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                        |
| go                       | 136 ms                                                 | 143 ms: 1.06x slower                                                         |
| scimark_sor              | 125 ms                                                 | 132 ms: 1.06x slower                                                         |
| spectral_norm            | 106 ms                                                 | 113 ms: 1.06x slower                                                         |
| nbody                    | 88.8 ms                                                | 95.1 ms: 1.07x slower                                                        |
| json                     | 4.77 ms                                                | 5.13 ms: 1.08x slower                                                        |
| pickle_list              | 4.62 us                                                | 4.97 us: 1.08x slower                                                        |
| logging_silent           | 99.1 ns                                                | 108 ns: 1.09x slower                                                         |
| fannkuch                 | 387 ms                                                 | 424 ms: 1.09x slower                                                         |
| pickle                   | 10.6 us                                                | 11.7 us: 1.10x slower                                                        |
| json_loads               | 25.2 us                                                | 27.9 us: 1.11x slower                                                        |
| mako                     | 10.7 ms                                                | 12.0 ms: 1.12x slower                                                        |
| richards_super           | 49.0 ms                                                | 54.8 ms: 1.12x slower                                                        |
| richards                 | 43.2 ms                                                | 48.5 ms: 1.12x slower                                                        |
| pickle_dict              | 31.6 us                                                | 35.6 us: 1.13x slower                                                        |
| regex_effbot             | 3.55 ms                                                | 4.06 ms: 1.14x slower                                                        |
| regex_v8                 | 22.3 ms                                                | 25.6 ms: 1.15x slower                                                        |
| telco                    | 6.87 ms                                                | 8.26 ms: 1.20x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                                 |

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed, pickle_pure_python, bench_mp_pool, nqueens
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.29% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
