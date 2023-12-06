
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.01x slower
- HPT reliability: 91.06%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.65 sec: 1.02x faster                                 |
| tornado_http   | 99.6 ms                                                | 96.1 ms: 1.04x faster                                  |
| Geometric mean | (ref)                                                  | 1.03x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                   |
| nbody          | 88.8 ms                                                | 89.5 ms: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                           |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 138 ms: 1.04x faster                                   |
| regex_effbot   | 3.55 ms                                                | 3.60 ms: 1.01x slower                                  |
| regex_dna      | 209 ms                                                 | 216 ms: 1.04x slower                                   |
| regex_v8       | 22.3 ms                                                | 24.1 ms: 1.08x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle             | 15.0 us                                                | 14.5 us: 1.03x faster                                  |
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                 |
| pickle_pure_python   | 309 us                                                 | 308 us: 1.00x faster                                   |
| xml_etree_process    | 58.6 ms                                                | 59.3 ms: 1.01x slower                                  |
| xml_etree_generate   | 84.8 ms                                                | 86.3 ms: 1.02x slower                                  |
| unpickle_list        | 4.95 us                                                | 5.05 us: 1.02x slower                                  |
| xml_etree_iterparse  | 104 ms                                                 | 106 ms: 1.02x slower                                   |
| xml_etree_parse      | 154 ms                                                 | 159 ms: 1.03x slower                                   |
| unpickle_pure_python | 218 us                                                 | 226 us: 1.03x slower                                   |
| pickle               | 10.6 us                                                | 11.1 us: 1.04x slower                                  |
| pickle_dict          | 31.6 us                                                | 33.9 us: 1.07x slower                                  |
| pickle_list          | 4.62 us                                                | 4.96 us: 1.07x slower                                  |
| json_dumps           | 9.85 ms                                                | 10.6 ms: 1.07x slower                                  |
| json_loads           | 25.2 us                                                | 27.7 us: 1.10x slower                                  |
| Geometric mean       | (ref)                                                  | 1.03x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.84 ms: 1.01x faster                                  |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                  |
| Geometric mean         | (ref)                                                  | 1.02x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.5 ms: 1.08x slower                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| gc_traversal             | 3.84 ms                                                | 3.52 ms: 1.09x faster                                  |
| asyncio_tcp              | 526 ms                                                 | 485 ms: 1.08x faster                                   |
| async_tree_none          | 469 ms                                                 | 436 ms: 1.08x faster                                   |
| raytrace                 | 294 ms                                                 | 275 ms: 1.07x faster                                   |
| deltablue                | 3.52 ms                                                | 3.32 ms: 1.06x faster                                  |
| logging_format           | 6.90 us                                                | 6.54 us: 1.06x faster                                  |
| crypto_pyaes             | 77.2 ms                                                | 73.2 ms: 1.06x faster                                  |
| regex_compile            | 144 ms                                                 | 138 ms: 1.04x faster                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.46 ms: 1.04x faster                                  |
| coverage                 | 94.2 ms                                                | 90.4 ms: 1.04x faster                                  |
| generators               | 31.1 ms                                                | 29.9 ms: 1.04x faster                                  |
| tornado_http             | 99.6 ms                                                | 96.1 ms: 1.04x faster                                  |
| scimark_monte_carlo      | 71.0 ms                                                | 68.7 ms: 1.03x faster                                  |
| logging_simple           | 6.18 us                                                | 5.98 us: 1.03x faster                                  |
| unpickle                 | 15.0 us                                                | 14.5 us: 1.03x faster                                  |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                  |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                  |
| dulwich_log              | 67.9 ms                                                | 66.6 ms: 1.02x faster                                  |
| async_tree_memoization   | 573 ms                                                 | 563 ms: 1.02x faster                                   |
| docutils                 | 2.70 sec                                               | 2.65 sec: 1.02x faster                                 |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                 |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.67 ms: 1.02x faster                                  |
| bench_thread_pool        | 827 us                                                 | 814 us: 1.02x faster                                   |
| chaos                    | 63.5 ms                                                | 62.6 ms: 1.02x faster                                  |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                   |
| mdp                      | 2.57 sec                                               | 2.53 sec: 1.01x faster                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.84 ms: 1.01x faster                                  |
| deepcopy                 | 355 us                                                 | 352 us: 1.01x faster                                   |
| nqueens                  | 81.1 ms                                                | 80.5 ms: 1.01x faster                                  |
| pickle_pure_python       | 309 us                                                 | 308 us: 1.00x faster                                   |
| deepcopy_reduce          | 3.14 us                                                | 3.15 us: 1.00x slower                                  |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                   |
| pprint_safe_repr         | 735 ms                                                 | 739 ms: 1.01x slower                                   |
| nbody                    | 88.8 ms                                                | 89.5 ms: 1.01x slower                                  |
| pycparser                | 1.15 sec                                               | 1.16 sec: 1.01x slower                                 |
| xml_etree_process        | 58.6 ms                                                | 59.3 ms: 1.01x slower                                  |
| comprehensions           | 20.4 us                                                | 20.7 us: 1.01x slower                                  |
| unpack_sequence          | 44.8 ns                                                | 45.4 ns: 1.01x slower                                  |
| regex_effbot             | 3.55 ms                                                | 3.60 ms: 1.01x slower                                  |
| hexiom                   | 6.12 ms                                                | 6.21 ms: 1.01x slower                                  |
| xml_etree_generate       | 84.8 ms                                                | 86.3 ms: 1.02x slower                                  |
| scimark_lu               | 114 ms                                                 | 116 ms: 1.02x slower                                   |
| unpickle_list            | 4.95 us                                                | 5.05 us: 1.02x slower                                  |
| sqlite_synth             | 2.76 us                                                | 2.82 us: 1.02x slower                                  |
| xml_etree_iterparse      | 104 ms                                                 | 106 ms: 1.02x slower                                   |
| async_tree_io            | 1.16 sec                                               | 1.18 sec: 1.02x slower                                 |
| scimark_sor              | 125 ms                                                 | 127 ms: 1.02x slower                                   |
| coroutines               | 22.4 ms                                                | 23.0 ms: 1.02x slower                                  |
| deepcopy_memo            | 37.4 us                                                | 38.5 us: 1.03x slower                                  |
| xml_etree_parse          | 154 ms                                                 | 159 ms: 1.03x slower                                   |
| typing_runtime_protocols | 146 us                                                 | 151 us: 1.03x slower                                   |
| pathlib                  | 18.5 ms                                                | 19.1 ms: 1.03x slower                                  |
| unpickle_pure_python     | 218 us                                                 | 226 us: 1.03x slower                                   |
| meteor_contest           | 105 ms                                                 | 108 ms: 1.03x slower                                   |
| regex_dna                | 209 ms                                                 | 216 ms: 1.04x slower                                   |
| scimark_fft              | 358 ms                                                 | 373 ms: 1.04x slower                                   |
| pickle                   | 10.6 us                                                | 11.1 us: 1.04x slower                                  |
| async_generators         | 440 ms                                                 | 460 ms: 1.05x slower                                   |
| go                       | 136 ms                                                 | 143 ms: 1.06x slower                                   |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                  |
| fannkuch                 | 387 ms                                                 | 412 ms: 1.06x slower                                   |
| pyflate                  | 450 ms                                                 | 480 ms: 1.07x slower                                   |
| logging_silent           | 99.1 ns                                                | 106 ns: 1.07x slower                                   |
| pickle_dict              | 31.6 us                                                | 33.9 us: 1.07x slower                                  |
| pickle_list              | 4.62 us                                                | 4.96 us: 1.07x slower                                  |
| json_dumps               | 9.85 ms                                                | 10.6 ms: 1.07x slower                                  |
| mako                     | 10.7 ms                                                | 11.5 ms: 1.08x slower                                  |
| regex_v8                 | 22.3 ms                                                | 24.1 ms: 1.08x slower                                  |
| json                     | 4.77 ms                                                | 5.14 ms: 1.08x slower                                  |
| json_loads               | 25.2 us                                                | 27.7 us: 1.10x slower                                  |
| richards_super           | 49.0 ms                                                | 54.3 ms: 1.11x slower                                  |
| richards                 | 43.2 ms                                                | 47.9 ms: 1.11x slower                                  |
| spectral_norm            | 106 ms                                                 | 119 ms: 1.12x slower                                   |
| telco                    | 6.87 ms                                                | 8.31 ms: 1.21x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x slower                                           |

Benchmark hidden because not significant (6): mypy2, bench_mp_pool, sqlglot_optimize, float, pprint_pformat, async_tree_cpu_io_mixed
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 91.06% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
