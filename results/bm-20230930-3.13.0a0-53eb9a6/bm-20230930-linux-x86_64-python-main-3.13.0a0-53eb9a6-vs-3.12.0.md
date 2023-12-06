
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.01x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.60 sec: 1.04x faster                                |
| tornado_http   | 99.6 ms                                                | 95.0 ms: 1.05x faster                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 80.7 ms                                                | 79.9 ms: 1.01x faster                                 |
| pidigits       | 187 ms                                                 | 194 ms: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 134 ms: 1.07x faster                                  |
| regex_dna      | 209 ms                                                 | 204 ms: 1.02x faster                                  |
| regex_effbot   | 3.55 ms                                                | 3.50 ms: 1.01x faster                                 |
| regex_v8       | 22.3 ms                                                | 23.4 ms: 1.05x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.11 sec: 1.05x faster                                |
| pickle_pure_python   | 309 us                                                 | 294 us: 1.05x faster                                  |
| unpickle_pure_python | 218 us                                                 | 211 us: 1.03x faster                                  |
| xml_etree_process    | 58.6 ms                                                | 56.8 ms: 1.03x faster                                 |
| xml_etree_generate   | 84.8 ms                                                | 83.3 ms: 1.02x faster                                 |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                 |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                  |
| pickle_dict          | 31.6 us                                                | 31.5 us: 1.00x faster                                 |
| unpickle_list        | 4.95 us                                                | 5.01 us: 1.01x slower                                 |
| json_loads           | 25.2 us                                                | 25.8 us: 1.02x slower                                 |
| pickle_list          | 4.62 us                                                | 4.72 us: 1.02x slower                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (3): xml_etree_parse, json_dumps, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.84 ms: 1.01x faster                                 |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                 |
| Geometric mean         | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.5 ms: 1.02x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-linux-x86_64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 68.4 ms: 1.13x faster                                 |
| raytrace                 | 294 ms                                                 | 265 ms: 1.11x faster                                  |
| coverage                 | 94.2 ms                                                | 85.3 ms: 1.10x faster                                 |
| generators               | 31.1 ms                                                | 28.4 ms: 1.10x faster                                 |
| async_tree_none          | 469 ms                                                 | 433 ms: 1.08x faster                                  |
| scimark_monte_carlo      | 71.0 ms                                                | 65.8 ms: 1.08x faster                                 |
| regex_compile            | 144 ms                                                 | 134 ms: 1.07x faster                                  |
| logging_format           | 6.90 us                                                | 6.47 us: 1.07x faster                                 |
| chaos                    | 63.5 ms                                                | 59.5 ms: 1.07x faster                                 |
| deltablue                | 3.52 ms                                                | 3.31 ms: 1.06x faster                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.25 ms: 1.05x faster                                 |
| logging_simple           | 6.18 us                                                | 5.87 us: 1.05x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.11 sec: 1.05x faster                                |
| asyncio_tcp              | 526 ms                                                 | 500 ms: 1.05x faster                                  |
| pickle_pure_python       | 309 us                                                 | 294 us: 1.05x faster                                  |
| sqlglot_transpile        | 1.64 ms                                                | 1.56 ms: 1.05x faster                                 |
| tornado_http             | 99.6 ms                                                | 95.0 ms: 1.05x faster                                 |
| deepcopy                 | 355 us                                                 | 341 us: 1.04x faster                                  |
| scimark_sor              | 125 ms                                                 | 120 ms: 1.04x faster                                  |
| docutils                 | 2.70 sec                                               | 2.60 sec: 1.04x faster                                |
| sqlglot_normalize        | 107 ms                                                 | 103 ms: 1.04x faster                                  |
| pprint_pformat           | 1.50 sec                                               | 1.45 sec: 1.04x faster                                |
| coroutines               | 22.4 ms                                                | 21.7 ms: 1.04x faster                                 |
| pprint_safe_repr         | 735 ms                                                 | 710 ms: 1.03x faster                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.04 us: 1.03x faster                                 |
| unpickle_pure_python     | 218 us                                                 | 211 us: 1.03x faster                                  |
| xml_etree_process        | 58.6 ms                                                | 56.8 ms: 1.03x faster                                 |
| deepcopy_memo            | 37.4 us                                                | 36.4 us: 1.03x faster                                 |
| typing_runtime_protocols | 146 us                                                 | 142 us: 1.03x faster                                  |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 695 ms: 1.03x faster                                  |
| dulwich_log              | 67.9 ms                                                | 66.1 ms: 1.03x faster                                 |
| bench_thread_pool        | 827 us                                                 | 806 us: 1.03x faster                                  |
| hexiom                   | 6.12 ms                                                | 5.97 ms: 1.03x faster                                 |
| mako                     | 10.7 ms                                                | 10.5 ms: 1.02x faster                                 |
| async_tree_memoization   | 573 ms                                                 | 559 ms: 1.02x faster                                  |
| regex_dna                | 209 ms                                                 | 204 ms: 1.02x faster                                  |
| sqlglot_optimize         | 53.3 ms                                                | 52.2 ms: 1.02x faster                                 |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.02x faster                                  |
| xml_etree_generate       | 84.8 ms                                                | 83.3 ms: 1.02x faster                                 |
| comprehensions           | 20.4 us                                                | 20.1 us: 1.02x faster                                 |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                 |
| regex_effbot             | 3.55 ms                                                | 3.50 ms: 1.01x faster                                 |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                  |
| float                    | 80.7 ms                                                | 79.9 ms: 1.01x faster                                 |
| fannkuch                 | 387 ms                                                 | 384 ms: 1.01x faster                                  |
| pycparser                | 1.15 sec                                               | 1.14 sec: 1.01x faster                                |
| python_startup_no_site   | 6.90 ms                                                | 6.84 ms: 1.01x faster                                 |
| spectral_norm            | 106 ms                                                 | 105 ms: 1.01x faster                                  |
| nqueens                  | 81.1 ms                                                | 80.5 ms: 1.01x faster                                 |
| async_generators         | 440 ms                                                 | 438 ms: 1.00x faster                                  |
| pickle_dict              | 31.6 us                                                | 31.5 us: 1.00x faster                                 |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.54 ms: 1.01x slower                                 |
| json                     | 4.77 ms                                                | 4.83 ms: 1.01x slower                                 |
| unpickle_list            | 4.95 us                                                | 5.01 us: 1.01x slower                                 |
| logging_silent           | 99.1 ns                                                | 100 ns: 1.01x slower                                  |
| json_loads               | 25.2 us                                                | 25.8 us: 1.02x slower                                 |
| go                       | 136 ms                                                 | 138 ms: 1.02x slower                                  |
| pyflate                  | 450 ms                                                 | 460 ms: 1.02x slower                                  |
| async_tree_io            | 1.16 sec                                               | 1.18 sec: 1.02x slower                                |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.85 ms: 1.02x slower                                 |
| gc_traversal             | 3.84 ms                                                | 3.93 ms: 1.02x slower                                 |
| pickle_list              | 4.62 us                                                | 4.72 us: 1.02x slower                                 |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.02x slower                                 |
| pidigits                 | 187 ms                                                 | 194 ms: 1.04x slower                                  |
| regex_v8                 | 22.3 ms                                                | 23.4 ms: 1.05x slower                                 |
| mdp                      | 2.57 sec                                               | 2.71 sec: 1.06x slower                                |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                 |
| richards                 | 43.2 ms                                                | 47.4 ms: 1.10x slower                                 |
| richards_super           | 49.0 ms                                                | 53.9 ms: 1.10x slower                                 |
| telco                    | 6.87 ms                                                | 7.97 ms: 1.16x slower                                 |
| mypy2                    | 344 ms                                                 | 450 ms: 1.31x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (9): xml_etree_parse, asyncio_tcp_ssl, bench_mp_pool, scimark_fft, json_dumps, nbody, unpickle, unpack_sequence, sqlite_synth
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
