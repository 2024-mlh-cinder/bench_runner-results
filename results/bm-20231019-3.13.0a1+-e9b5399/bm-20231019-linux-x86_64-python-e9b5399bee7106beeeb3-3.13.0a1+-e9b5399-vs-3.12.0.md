
# Results vs. 3.12.0

- fork: python
- ref: e9b5399bee7106beeeb3
- machine: linux-x86_64
- commit hash: e9b5399
- commit date: 2023-10-19
- overall geometric mean: 1.02x slower
- HPT reliability: 95.38%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.67 sec: 1.01x faster                                                 |
| tornado_http   | 99.6 ms                                                | 95.9 ms: 1.04x faster                                                  |
| Geometric mean | (ref)                                                  | 1.03x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 81.7 ms: 1.01x slower                                                  |
| nbody          | 88.8 ms                                                | 91.5 ms: 1.03x slower                                                  |
| pidigits       | 187 ms                                                 | 195 ms: 1.05x slower                                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                   |
| regex_effbot   | 3.55 ms                                                | 3.63 ms: 1.02x slower                                                  |
| regex_dna      | 209 ms                                                 | 221 ms: 1.06x slower                                                   |
| regex_v8       | 22.3 ms                                                | 24.5 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                 |
| pickle_pure_python   | 309 us                                                 | 306 us: 1.01x faster                                                   |
| xml_etree_generate   | 84.8 ms                                                | 86.4 ms: 1.02x slower                                                  |
| xml_etree_process    | 58.6 ms                                                | 59.7 ms: 1.02x slower                                                  |
| unpickle_pure_python | 218 us                                                 | 223 us: 1.02x slower                                                   |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.03x slower                                                   |
| unpickle_list        | 4.95 us                                                | 5.08 us: 1.03x slower                                                  |
| xml_etree_parse      | 154 ms                                                 | 159 ms: 1.03x slower                                                   |
| json_dumps           | 9.85 ms                                                | 10.5 ms: 1.06x slower                                                  |
| pickle               | 10.6 us                                                | 11.5 us: 1.08x slower                                                  |
| json_loads           | 25.2 us                                                | 27.8 us: 1.10x slower                                                  |
| pickle_list          | 4.62 us                                                | 5.14 us: 1.11x slower                                                  |
| pickle_dict          | 31.6 us                                                | 36.1 us: 1.14x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                           |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.90 ms: 1.00x faster                                                  |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.7 ms: 1.09x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| asyncio_tcp              | 526 ms                                                 | 477 ms: 1.10x faster                                                   |
| logging_format           | 6.90 us                                                | 6.43 us: 1.07x faster                                                  |
| async_tree_none          | 469 ms                                                 | 438 ms: 1.07x faster                                                   |
| crypto_pyaes             | 77.2 ms                                                | 72.2 ms: 1.07x faster                                                  |
| logging_simple           | 6.18 us                                                | 5.80 us: 1.06x faster                                                  |
| deltablue                | 3.52 ms                                                | 3.32 ms: 1.06x faster                                                  |
| raytrace                 | 294 ms                                                 | 278 ms: 1.06x faster                                                   |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                   |
| generators               | 31.1 ms                                                | 29.8 ms: 1.04x faster                                                  |
| coverage                 | 94.2 ms                                                | 90.5 ms: 1.04x faster                                                  |
| tornado_http             | 99.6 ms                                                | 95.9 ms: 1.04x faster                                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.47 ms: 1.03x faster                                                  |
| tomli_loads              | 2.22 sec                                               | 2.15 sec: 1.03x faster                                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.03x faster                                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.63 ms: 1.03x faster                                                  |
| nqueens                  | 81.1 ms                                                | 79.4 ms: 1.02x faster                                                  |
| async_tree_memoization   | 573 ms                                                 | 561 ms: 1.02x faster                                                   |
| scimark_monte_carlo      | 71.0 ms                                                | 69.5 ms: 1.02x faster                                                  |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                                  |
| chaos                    | 63.5 ms                                                | 62.3 ms: 1.02x faster                                                  |
| bench_thread_pool        | 827 us                                                 | 813 us: 1.02x faster                                                   |
| docutils                 | 2.70 sec                                               | 2.67 sec: 1.01x faster                                                 |
| pickle_pure_python       | 309 us                                                 | 306 us: 1.01x faster                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                                                 |
| coroutines               | 22.4 ms                                                | 22.3 ms: 1.01x faster                                                  |
| dulwich_log              | 67.9 ms                                                | 67.4 ms: 1.01x faster                                                  |
| sqlglot_normalize        | 107 ms                                                 | 107 ms: 1.01x faster                                                   |
| mdp                      | 2.57 sec                                               | 2.55 sec: 1.01x faster                                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.90 ms: 1.00x faster                                                  |
| hexiom                   | 6.12 ms                                                | 6.15 ms: 1.00x slower                                                  |
| gc_traversal             | 3.84 ms                                                | 3.87 ms: 1.01x slower                                                  |
| sqlglot_optimize         | 53.3 ms                                                | 53.7 ms: 1.01x slower                                                  |
| scimark_sor              | 125 ms                                                 | 126 ms: 1.01x slower                                                   |
| pprint_pformat           | 1.50 sec                                               | 1.52 sec: 1.01x slower                                                 |
| float                    | 80.7 ms                                                | 81.7 ms: 1.01x slower                                                  |
| comprehensions           | 20.4 us                                                | 20.7 us: 1.01x slower                                                  |
| pycparser                | 1.15 sec                                               | 1.17 sec: 1.01x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.18 sec: 1.02x slower                                                 |
| scimark_fft              | 358 ms                                                 | 365 ms: 1.02x slower                                                   |
| xml_etree_generate       | 84.8 ms                                                | 86.4 ms: 1.02x slower                                                  |
| xml_etree_process        | 58.6 ms                                                | 59.7 ms: 1.02x slower                                                  |
| pprint_safe_repr         | 735 ms                                                 | 749 ms: 1.02x slower                                                   |
| unpickle_pure_python     | 218 us                                                 | 223 us: 1.02x slower                                                   |
| regex_effbot             | 3.55 ms                                                | 3.63 ms: 1.02x slower                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.03x slower                                                   |
| async_generators         | 440 ms                                                 | 452 ms: 1.03x slower                                                   |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.03x slower                                                  |
| unpickle_list            | 4.95 us                                                | 5.08 us: 1.03x slower                                                  |
| nbody                    | 88.8 ms                                                | 91.5 ms: 1.03x slower                                                  |
| xml_etree_parse          | 154 ms                                                 | 159 ms: 1.03x slower                                                   |
| sqlite_synth             | 2.76 us                                                | 2.85 us: 1.03x slower                                                  |
| pyflate                  | 450 ms                                                 | 470 ms: 1.04x slower                                                   |
| pidigits                 | 187 ms                                                 | 195 ms: 1.05x slower                                                   |
| meteor_contest           | 105 ms                                                 | 110 ms: 1.05x slower                                                   |
| go                       | 136 ms                                                 | 143 ms: 1.05x slower                                                   |
| regex_dna                | 209 ms                                                 | 221 ms: 1.06x slower                                                   |
| fannkuch                 | 387 ms                                                 | 410 ms: 1.06x slower                                                   |
| json_dumps               | 9.85 ms                                                | 10.5 ms: 1.06x slower                                                  |
| typing_runtime_protocols | 146 us                                                 | 155 us: 1.06x slower                                                   |
| json                     | 4.77 ms                                                | 5.08 ms: 1.07x slower                                                  |
| spectral_norm            | 106 ms                                                 | 113 ms: 1.07x slower                                                   |
| deepcopy_memo            | 37.4 us                                                | 40.0 us: 1.07x slower                                                  |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                  |
| pickle                   | 10.6 us                                                | 11.5 us: 1.08x slower                                                  |
| mako                     | 10.7 ms                                                | 11.7 ms: 1.09x slower                                                  |
| regex_v8                 | 22.3 ms                                                | 24.5 ms: 1.10x slower                                                  |
| logging_silent           | 99.1 ns                                                | 109 ns: 1.10x slower                                                   |
| json_loads               | 25.2 us                                                | 27.8 us: 1.10x slower                                                  |
| richards_super           | 49.0 ms                                                | 54.3 ms: 1.11x slower                                                  |
| pickle_list              | 4.62 us                                                | 5.14 us: 1.11x slower                                                  |
| richards                 | 43.2 ms                                                | 48.4 ms: 1.12x slower                                                  |
| unpack_sequence          | 44.8 ns                                                | 51.3 ns: 1.14x slower                                                  |
| pickle_dict              | 31.6 us                                                | 36.1 us: 1.14x slower                                                  |
| telco                    | 6.87 ms                                                | 8.39 ms: 1.22x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (7): deepcopy_reduce, bench_mp_pool, unpickle, mypy2, deepcopy, async_tree_cpu_io_mixed, scimark_lu
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 95.38% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
