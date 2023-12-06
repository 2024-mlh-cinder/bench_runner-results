
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 8e56d55
- commit date: 2023-10-07
- overall geometric mean: 1.02x slower
- HPT reliability: 98.71%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.63 sec: 1.03x faster                                |
| tornado_http   | 99.6 ms                                                | 96.5 ms: 1.03x faster                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                  |
| float          | 80.7 ms                                                | 82.7 ms: 1.02x slower                                 |
| nbody          | 88.8 ms                                                | 91.4 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 139 ms: 1.04x faster                                  |
| regex_dna      | 209 ms                                                 | 211 ms: 1.01x slower                                  |
| regex_effbot   | 3.55 ms                                                | 3.65 ms: 1.03x slower                                 |
| regex_v8       | 22.3 ms                                                | 25.5 ms: 1.14x slower                                 |
| Geometric mean | (ref)                                                  | 1.04x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.17 sec: 1.02x faster                                |
| pickle_pure_python   | 309 us                                                 | 307 us: 1.01x faster                                  |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                  |
| xml_etree_process    | 58.6 ms                                                | 59.6 ms: 1.02x slower                                 |
| xml_etree_generate   | 84.8 ms                                                | 86.7 ms: 1.02x slower                                 |
| unpickle_list        | 4.95 us                                                | 5.08 us: 1.03x slower                                 |
| xml_etree_parse      | 154 ms                                                 | 158 ms: 1.03x slower                                  |
| unpickle_pure_python | 218 us                                                 | 225 us: 1.03x slower                                  |
| json_dumps           | 9.85 ms                                                | 10.5 ms: 1.06x slower                                 |
| pickle_dict          | 31.6 us                                                | 34.2 us: 1.08x slower                                 |
| pickle               | 10.6 us                                                | 11.6 us: 1.09x slower                                 |
| pickle_list          | 4.62 us                                                | 5.18 us: 1.12x slower                                 |
| json_loads           | 25.2 us                                                | 28.4 us: 1.13x slower                                 |
| Geometric mean       | (ref)                                                  | 1.04x slower                                          |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.85 ms: 1.01x faster                                 |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.06x slower                                 |
| Geometric mean         | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.8 ms: 1.10x slower                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-linux-x86_64-python-main-3.13.0a0-8e56d55 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 474 ms: 1.11x faster                                  |
| generators               | 31.1 ms                                                | 29.0 ms: 1.07x faster                                 |
| logging_format           | 6.90 us                                                | 6.48 us: 1.07x faster                                 |
| async_tree_none          | 469 ms                                                 | 440 ms: 1.07x faster                                  |
| crypto_pyaes             | 77.2 ms                                                | 72.8 ms: 1.06x faster                                 |
| deltablue                | 3.52 ms                                                | 3.32 ms: 1.06x faster                                 |
| raytrace                 | 294 ms                                                 | 278 ms: 1.06x faster                                  |
| logging_simple           | 6.18 us                                                | 5.86 us: 1.05x faster                                 |
| coverage                 | 94.2 ms                                                | 90.4 ms: 1.04x faster                                 |
| regex_compile            | 144 ms                                                 | 139 ms: 1.04x faster                                  |
| tornado_http             | 99.6 ms                                                | 96.5 ms: 1.03x faster                                 |
| chaos                    | 63.5 ms                                                | 61.8 ms: 1.03x faster                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 69.2 ms: 1.03x faster                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.03x faster                                 |
| docutils                 | 2.70 sec                                               | 2.63 sec: 1.03x faster                                |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.17 sec: 1.02x faster                                |
| bench_thread_pool        | 827 us                                                 | 813 us: 1.02x faster                                  |
| nqueens                  | 81.1 ms                                                | 79.8 ms: 1.02x faster                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.77 sec: 1.01x faster                                |
| async_tree_memoization   | 573 ms                                                 | 567 ms: 1.01x faster                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.70 ms: 1.01x faster                                 |
| pickle_pure_python       | 309 us                                                 | 307 us: 1.01x faster                                  |
| python_startup_no_site   | 6.90 ms                                                | 6.85 ms: 1.01x faster                                 |
| dulwich_log              | 67.9 ms                                                | 67.4 ms: 1.01x faster                                 |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                  |
| gc_traversal             | 3.84 ms                                                | 3.85 ms: 1.00x slower                                 |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.53 ms: 1.01x slower                                 |
| sqlglot_optimize         | 53.3 ms                                                | 53.6 ms: 1.01x slower                                 |
| scimark_sor              | 125 ms                                                 | 126 ms: 1.01x slower                                  |
| scimark_lu               | 114 ms                                                 | 115 ms: 1.01x slower                                  |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                  |
| pprint_pformat           | 1.50 sec                                               | 1.52 sec: 1.01x slower                                |
| pprint_safe_repr         | 735 ms                                                 | 744 ms: 1.01x slower                                  |
| regex_dna                | 209 ms                                                 | 211 ms: 1.01x slower                                  |
| mdp                      | 2.57 sec                                               | 2.60 sec: 1.01x slower                                |
| deepcopy_reduce          | 3.14 us                                                | 3.19 us: 1.02x slower                                 |
| xml_etree_process        | 58.6 ms                                                | 59.6 ms: 1.02x slower                                 |
| xml_etree_generate       | 84.8 ms                                                | 86.7 ms: 1.02x slower                                 |
| float                    | 80.7 ms                                                | 82.7 ms: 1.02x slower                                 |
| unpickle_list            | 4.95 us                                                | 5.08 us: 1.03x slower                                 |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.03x slower                                 |
| xml_etree_parse          | 154 ms                                                 | 158 ms: 1.03x slower                                  |
| nbody                    | 88.8 ms                                                | 91.4 ms: 1.03x slower                                 |
| regex_effbot             | 3.55 ms                                                | 3.65 ms: 1.03x slower                                 |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                |
| hexiom                   | 6.12 ms                                                | 6.31 ms: 1.03x slower                                 |
| scimark_fft              | 358 ms                                                 | 370 ms: 1.03x slower                                  |
| pyflate                  | 450 ms                                                 | 465 ms: 1.03x slower                                  |
| unpickle_pure_python     | 218 us                                                 | 225 us: 1.03x slower                                  |
| comprehensions           | 20.4 us                                                | 21.1 us: 1.03x slower                                 |
| sqlite_synth             | 2.76 us                                                | 2.85 us: 1.03x slower                                 |
| coroutines               | 22.4 ms                                                | 23.3 ms: 1.04x slower                                 |
| deepcopy_memo            | 37.4 us                                                | 38.9 us: 1.04x slower                                 |
| meteor_contest           | 105 ms                                                 | 109 ms: 1.04x slower                                  |
| typing_runtime_protocols | 146 us                                                 | 154 us: 1.05x slower                                  |
| pycparser                | 1.15 sec                                               | 1.21 sec: 1.06x slower                                |
| fannkuch                 | 387 ms                                                 | 412 ms: 1.06x slower                                  |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.06x slower                                 |
| json_dumps               | 9.85 ms                                                | 10.5 ms: 1.06x slower                                 |
| async_generators         | 440 ms                                                 | 471 ms: 1.07x slower                                  |
| spectral_norm            | 106 ms                                                 | 114 ms: 1.07x slower                                  |
| json                     | 4.77 ms                                                | 5.14 ms: 1.08x slower                                 |
| go                       | 136 ms                                                 | 146 ms: 1.08x slower                                  |
| pickle_dict              | 31.6 us                                                | 34.2 us: 1.08x slower                                 |
| logging_silent           | 99.1 ns                                                | 107 ns: 1.08x slower                                  |
| pickle                   | 10.6 us                                                | 11.6 us: 1.09x slower                                 |
| mako                     | 10.7 ms                                                | 11.8 ms: 1.10x slower                                 |
| richards                 | 43.2 ms                                                | 47.8 ms: 1.11x slower                                 |
| richards_super           | 49.0 ms                                                | 54.2 ms: 1.11x slower                                 |
| pickle_list              | 4.62 us                                                | 5.18 us: 1.12x slower                                 |
| json_loads               | 25.2 us                                                | 28.4 us: 1.13x slower                                 |
| regex_v8                 | 22.3 ms                                                | 25.5 ms: 1.14x slower                                 |
| telco                    | 6.87 ms                                                | 8.23 ms: 1.20x slower                                 |
| unpack_sequence          | 44.8 ns                                                | 55.1 ns: 1.23x slower                                 |
| Geometric mean           | (ref)                                                  | 1.02x slower                                          |

Benchmark hidden because not significant (5): unpickle, deepcopy, bench_mp_pool, async_tree_cpu_io_mixed, mypy2
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.71% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
