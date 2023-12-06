
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.01x slower
- HPT reliability: 96.69%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.67 sec: 1.01x faster                                               |
| tornado_http   | 99.6 ms                                                | 96.6 ms: 1.03x faster                                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                 |
| float          | 80.7 ms                                                | 81.7 ms: 1.01x slower                                                |
| nbody          | 88.8 ms                                                | 95.5 ms: 1.07x slower                                                |
| Geometric mean | (ref)                                                  | 1.03x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 141 ms: 1.02x faster                                                 |
| regex_effbot   | 3.55 ms                                                | 3.54 ms: 1.00x faster                                                |
| regex_dna      | 209 ms                                                 | 211 ms: 1.01x slower                                                 |
| regex_v8       | 22.3 ms                                                | 25.0 ms: 1.12x slower                                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.1 us: 1.06x faster                                                |
| pickle_pure_python   | 309 us                                                 | 297 us: 1.04x faster                                                 |
| pickle_list          | 4.62 us                                                | 4.46 us: 1.03x faster                                                |
| tomli_loads          | 2.22 sec                                               | 2.15 sec: 1.03x faster                                               |
| unpickle_list        | 4.95 us                                                | 4.82 us: 1.03x faster                                                |
| xml_etree_generate   | 84.8 ms                                                | 83.5 ms: 1.02x faster                                                |
| xml_etree_process    | 58.6 ms                                                | 57.8 ms: 1.01x faster                                                |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                 |
| pickle_dict          | 31.6 us                                                | 31.8 us: 1.01x slower                                                |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                                 |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                                |
| unpickle_pure_python | 218 us                                                 | 228 us: 1.04x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                         |

Benchmark hidden because not significant (2): json_loads, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.52 ms: 1.00x slower                                                |
| python_startup_no_site | 6.90 ms                                                | 7.00 ms: 1.02x slower                                                |
| Geometric mean         | (ref)                                                  | 1.01x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.2 ms: 1.04x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 85.5 ms: 1.10x faster                                                |
| crypto_pyaes             | 77.2 ms                                                | 71.8 ms: 1.07x faster                                                |
| asyncio_tcp              | 526 ms                                                 | 493 ms: 1.07x faster                                                 |
| unpickle                 | 15.0 us                                                | 14.1 us: 1.06x faster                                                |
| raytrace                 | 294 ms                                                 | 277 ms: 1.06x faster                                                 |
| async_tree_none          | 469 ms                                                 | 442 ms: 1.06x faster                                                 |
| generators               | 31.1 ms                                                | 29.5 ms: 1.05x faster                                                |
| scimark_monte_carlo      | 71.0 ms                                                | 67.6 ms: 1.05x faster                                                |
| logging_format           | 6.90 us                                                | 6.60 us: 1.05x faster                                                |
| pickle_pure_python       | 309 us                                                 | 297 us: 1.04x faster                                                 |
| logging_simple           | 6.18 us                                                | 5.96 us: 1.04x faster                                                |
| deltablue                | 3.52 ms                                                | 3.40 ms: 1.04x faster                                                |
| pickle_list              | 4.62 us                                                | 4.46 us: 1.03x faster                                                |
| tornado_http             | 99.6 ms                                                | 96.6 ms: 1.03x faster                                                |
| create_gc_cycles         | 1.52 ms                                                | 1.48 ms: 1.03x faster                                                |
| tomli_loads              | 2.22 sec                                               | 2.15 sec: 1.03x faster                                               |
| unpickle_list            | 4.95 us                                                | 4.82 us: 1.03x faster                                                |
| regex_compile            | 144 ms                                                 | 141 ms: 1.02x faster                                                 |
| deepcopy_reduce          | 3.14 us                                                | 3.07 us: 1.02x faster                                                |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.02x faster                                                |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                                 |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.02x faster                                                |
| xml_etree_generate       | 84.8 ms                                                | 83.5 ms: 1.02x faster                                                |
| chaos                    | 63.5 ms                                                | 62.6 ms: 1.01x faster                                                |
| sqlglot_transpile        | 1.64 ms                                                | 1.62 ms: 1.01x faster                                                |
| xml_etree_process        | 58.6 ms                                                | 57.8 ms: 1.01x faster                                                |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                 |
| docutils                 | 2.70 sec                                               | 2.67 sec: 1.01x faster                                               |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                                |
| deepcopy                 | 355 us                                                 | 353 us: 1.01x faster                                                 |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                 |
| regex_effbot             | 3.55 ms                                                | 3.54 ms: 1.00x faster                                                |
| pprint_safe_repr         | 735 ms                                                 | 738 ms: 1.00x slower                                                 |
| python_startup           | 9.47 ms                                                | 9.52 ms: 1.00x slower                                                |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                 |
| typing_runtime_protocols | 146 us                                                 | 147 us: 1.01x slower                                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.01x slower                                               |
| pickle_dict              | 31.6 us                                                | 31.8 us: 1.01x slower                                                |
| scimark_fft              | 358 ms                                                 | 361 ms: 1.01x slower                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.01x slower                                               |
| sqlglot_optimize         | 53.3 ms                                                | 53.9 ms: 1.01x slower                                                |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                                 |
| regex_dna                | 209 ms                                                 | 211 ms: 1.01x slower                                                 |
| float                    | 80.7 ms                                                | 81.7 ms: 1.01x slower                                                |
| bench_thread_pool        | 827 us                                                 | 839 us: 1.01x slower                                                 |
| python_startup_no_site   | 6.90 ms                                                | 7.00 ms: 1.02x slower                                                |
| mypy2                    | 344 ms                                                 | 349 ms: 1.02x slower                                                 |
| pathlib                  | 18.5 ms                                                | 18.8 ms: 1.02x slower                                                |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                                |
| pycparser                | 1.15 sec                                               | 1.17 sec: 1.02x slower                                               |
| gc_traversal             | 3.84 ms                                                | 3.94 ms: 1.03x slower                                                |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.03x slower                                               |
| deepcopy_memo            | 37.4 us                                                | 38.8 us: 1.04x slower                                                |
| fannkuch                 | 387 ms                                                 | 402 ms: 1.04x slower                                                 |
| pyflate                  | 450 ms                                                 | 469 ms: 1.04x slower                                                 |
| unpickle_pure_python     | 218 us                                                 | 228 us: 1.04x slower                                                 |
| mako                     | 10.7 ms                                                | 11.2 ms: 1.04x slower                                                |
| logging_silent           | 99.1 ns                                                | 104 ns: 1.05x slower                                                 |
| spectral_norm            | 106 ms                                                 | 112 ms: 1.05x slower                                                 |
| meteor_contest           | 105 ms                                                 | 111 ms: 1.06x slower                                                 |
| async_generators         | 440 ms                                                 | 470 ms: 1.07x slower                                                 |
| go                       | 136 ms                                                 | 145 ms: 1.07x slower                                                 |
| nbody                    | 88.8 ms                                                | 95.5 ms: 1.07x slower                                                |
| mdp                      | 2.57 sec                                               | 2.78 sec: 1.08x slower                                               |
| nqueens                  | 81.1 ms                                                | 87.9 ms: 1.08x slower                                                |
| richards                 | 43.2 ms                                                | 47.9 ms: 1.11x slower                                                |
| richards_super           | 49.0 ms                                                | 54.5 ms: 1.11x slower                                                |
| regex_v8                 | 22.3 ms                                                | 25.0 ms: 1.12x slower                                                |
| hexiom                   | 6.12 ms                                                | 6.86 ms: 1.12x slower                                                |
| comprehensions           | 20.4 us                                                | 23.0 us: 1.12x slower                                                |
| unpack_sequence          | 44.8 ns                                                | 51.7 ns: 1.15x slower                                                |
| telco                    | 6.87 ms                                                | 8.24 ms: 1.20x slower                                                |
| dask                     | 365 ms                                                 | 530 ms: 1.45x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                         |

Benchmark hidden because not significant (9): async_tree_cpu_io_mixed, scimark_sparse_mat_mult, async_tree_memoization, json, json_loads, json_dumps, bench_mp_pool, dulwich_log, scimark_lu
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 96.69% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
