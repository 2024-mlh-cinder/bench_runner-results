
# Results vs. 3.12.0

- fork: brandtbucher
- ref: kwnames_frame
- machine: linux-x86_64
- commit hash: 7f16231
- commit date: 2023-08-11
- overall geometric mean: 1.00x slower
- HPT reliability: 94.44%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.63 sec: 1.03x faster                                               |
| tornado_http   | 99.6 ms                                                | 96.2 ms: 1.03x faster                                                |
| Geometric mean | (ref)                                                  | 1.03x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 80.2 ms: 1.01x faster                                                |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                 |
| nbody          | 88.8 ms                                                | 93.9 ms: 1.06x slower                                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                 |
| regex_dna      | 209 ms                                                 | 213 ms: 1.02x slower                                                 |
| regex_v8       | 22.3 ms                                                | 25.1 ms: 1.12x slower                                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                                         |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_list          | 4.62 us                                                | 4.38 us: 1.05x faster                                                |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                               |
| pickle_pure_python   | 309 us                                                 | 303 us: 1.02x faster                                                 |
| pickle_dict          | 31.6 us                                                | 31.1 us: 1.02x faster                                                |
| pickle               | 10.6 us                                                | 10.4 us: 1.02x faster                                                |
| unpickle_pure_python | 218 us                                                 | 216 us: 1.01x faster                                                 |
| unpickle_list        | 4.95 us                                                | 4.89 us: 1.01x faster                                                |
| xml_etree_process    | 58.6 ms                                                | 57.9 ms: 1.01x faster                                                |
| json_dumps           | 9.85 ms                                                | 9.78 ms: 1.01x faster                                                |
| json_loads           | 25.2 us                                                | 25.5 us: 1.01x slower                                                |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                         |

Benchmark hidden because not significant (4): xml_etree_parse, xml_etree_iterparse, xml_etree_generate, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.42 ms: 1.00x faster                                                |
| python_startup_no_site | 6.90 ms                                                | 6.90 ms: 1.00x slower                                                |
| Geometric mean         | (ref)                                                  | 1.00x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-brandtbucher-kwnames_frame-3.13.0a0-7f16231 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpack_sequence          | 44.8 ns                                                | 40.6 ns: 1.10x faster                                                |
| crypto_pyaes             | 77.2 ms                                                | 70.2 ms: 1.10x faster                                                |
| coverage                 | 94.2 ms                                                | 86.0 ms: 1.09x faster                                                |
| asyncio_tcp              | 526 ms                                                 | 489 ms: 1.08x faster                                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 66.5 ms: 1.07x faster                                                |
| raytrace                 | 294 ms                                                 | 276 ms: 1.07x faster                                                 |
| generators               | 31.1 ms                                                | 29.3 ms: 1.06x faster                                                |
| deltablue                | 3.52 ms                                                | 3.32 ms: 1.06x faster                                                |
| pickle_list              | 4.62 us                                                | 4.38 us: 1.05x faster                                                |
| logging_format           | 6.90 us                                                | 6.56 us: 1.05x faster                                                |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                 |
| async_tree_none          | 469 ms                                                 | 448 ms: 1.05x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 2.12 sec: 1.05x faster                                               |
| chaos                    | 63.5 ms                                                | 61.0 ms: 1.04x faster                                                |
| scimark_lu               | 114 ms                                                 | 110 ms: 1.04x faster                                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.04x faster                                                |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.58 ms: 1.04x faster                                                |
| tornado_http             | 99.6 ms                                                | 96.2 ms: 1.03x faster                                                |
| logging_simple           | 6.18 us                                                | 5.98 us: 1.03x faster                                                |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.03x faster                                                |
| docutils                 | 2.70 sec                                               | 2.63 sec: 1.03x faster                                               |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                                 |
| dulwich_log              | 67.9 ms                                                | 66.5 ms: 1.02x faster                                                |
| create_gc_cycles         | 1.52 ms                                                | 1.49 ms: 1.02x faster                                                |
| pickle_pure_python       | 309 us                                                 | 303 us: 1.02x faster                                                 |
| typing_runtime_protocols | 146 us                                                 | 143 us: 1.02x faster                                                 |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.02x faster                                                 |
| pickle_dict              | 31.6 us                                                | 31.1 us: 1.02x faster                                                |
| pickle                   | 10.6 us                                                | 10.4 us: 1.02x faster                                                |
| scimark_fft              | 358 ms                                                 | 354 ms: 1.01x faster                                                 |
| unpickle_pure_python     | 218 us                                                 | 216 us: 1.01x faster                                                 |
| mypy2                    | 344 ms                                                 | 340 ms: 1.01x faster                                                 |
| unpickle_list            | 4.95 us                                                | 4.89 us: 1.01x faster                                                |
| xml_etree_process        | 58.6 ms                                                | 57.9 ms: 1.01x faster                                                |
| sqlglot_optimize         | 53.3 ms                                                | 52.8 ms: 1.01x faster                                                |
| pyflate                  | 450 ms                                                 | 446 ms: 1.01x faster                                                 |
| hexiom                   | 6.12 ms                                                | 6.07 ms: 1.01x faster                                                |
| pprint_safe_repr         | 735 ms                                                 | 729 ms: 1.01x faster                                                 |
| mdp                      | 2.57 sec                                               | 2.55 sec: 1.01x faster                                               |
| pprint_pformat           | 1.50 sec                                               | 1.49 sec: 1.01x faster                                               |
| json_dumps               | 9.85 ms                                                | 9.78 ms: 1.01x faster                                                |
| float                    | 80.7 ms                                                | 80.2 ms: 1.01x faster                                                |
| python_startup           | 9.47 ms                                                | 9.42 ms: 1.00x faster                                                |
| bench_thread_pool        | 827 us                                                 | 825 us: 1.00x faster                                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.90 ms: 1.00x slower                                                |
| deepcopy_memo            | 37.4 us                                                | 37.6 us: 1.01x slower                                                |
| async_generators         | 440 ms                                                 | 443 ms: 1.01x slower                                                 |
| deepcopy_reduce          | 3.14 us                                                | 3.16 us: 1.01x slower                                                |
| nqueens                  | 81.1 ms                                                | 81.9 ms: 1.01x slower                                                |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                |
| json_loads               | 25.2 us                                                | 25.5 us: 1.01x slower                                                |
| async_tree_memoization   | 573 ms                                                 | 580 ms: 1.01x slower                                                 |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                 |
| pycparser                | 1.15 sec                                               | 1.17 sec: 1.02x slower                                               |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.02x slower                                                 |
| fannkuch                 | 387 ms                                                 | 394 ms: 1.02x slower                                                 |
| regex_dna                | 209 ms                                                 | 213 ms: 1.02x slower                                                 |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.02x slower                                                |
| coroutines               | 22.4 ms                                                | 23.1 ms: 1.03x slower                                                |
| json                     | 4.77 ms                                                | 4.91 ms: 1.03x slower                                                |
| go                       | 136 ms                                                 | 140 ms: 1.03x slower                                                 |
| comprehensions           | 20.4 us                                                | 21.1 us: 1.03x slower                                                |
| spectral_norm            | 106 ms                                                 | 110 ms: 1.04x slower                                                 |
| nbody                    | 88.8 ms                                                | 93.9 ms: 1.06x slower                                                |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.23 sec: 1.06x slower                                               |
| richards                 | 43.2 ms                                                | 47.6 ms: 1.10x slower                                                |
| richards_super           | 49.0 ms                                                | 54.8 ms: 1.12x slower                                                |
| regex_v8                 | 22.3 ms                                                | 25.1 ms: 1.12x slower                                                |
| gc_traversal             | 3.84 ms                                                | 4.33 ms: 1.13x slower                                                |
| telco                    | 6.87 ms                                                | 8.01 ms: 1.17x slower                                                |
| dask                     | 365 ms                                                 | 525 ms: 1.44x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.00x slower                                                         |

Benchmark hidden because not significant (10): sqlite_synth, xml_etree_parse, deepcopy, xml_etree_iterparse, xml_etree_generate, bench_mp_pool, asyncio_tcp_ssl, regex_effbot, unpickle, async_tree_cpu_io_mixed
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 94.44% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
