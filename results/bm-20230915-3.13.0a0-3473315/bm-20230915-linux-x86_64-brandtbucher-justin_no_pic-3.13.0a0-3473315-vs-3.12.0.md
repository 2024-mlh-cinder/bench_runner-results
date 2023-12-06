
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3473315
- commit date: 2023-09-15
- overall geometric mean: 1.00x slower
- HPT reliability: 80.06%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.67 sec: 1.01x faster                                               |
| tornado_http   | 99.6 ms                                                | 96.8 ms: 1.03x faster                                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 88.8 ms                                                | 87.9 ms: 1.01x faster                                                |
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                                 |
| float          | 80.7 ms                                                | 81.5 ms: 1.01x slower                                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.40 ms: 1.04x faster                                                |
| regex_dna      | 209 ms                                                 | 204 ms: 1.02x faster                                                 |
| regex_compile  | 144 ms                                                 | 142 ms: 1.02x faster                                                 |
| regex_v8       | 22.3 ms                                                | 23.4 ms: 1.05x slower                                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.06 sec: 1.07x faster                                               |
| unpickle             | 15.0 us                                                | 14.1 us: 1.06x faster                                                |
| pickle_pure_python   | 309 us                                                 | 300 us: 1.03x faster                                                 |
| pickle               | 10.6 us                                                | 10.3 us: 1.03x faster                                                |
| xml_etree_process    | 58.6 ms                                                | 57.4 ms: 1.02x faster                                                |
| xml_etree_generate   | 84.8 ms                                                | 83.4 ms: 1.02x faster                                                |
| unpickle_list        | 4.95 us                                                | 4.87 us: 1.01x faster                                                |
| pickle_dict          | 31.6 us                                                | 31.2 us: 1.01x faster                                                |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                 |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                 |
| json_dumps           | 9.85 ms                                                | 9.77 ms: 1.01x faster                                                |
| pickle_list          | 4.62 us                                                | 4.64 us: 1.00x slower                                                |
| unpickle_pure_python | 218 us                                                 | 225 us: 1.03x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                         |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.82 ms: 1.01x faster                                                |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 84.5 ms: 1.11x faster                                                |
| generators               | 31.1 ms                                                | 28.5 ms: 1.09x faster                                                |
| raytrace                 | 294 ms                                                 | 270 ms: 1.09x faster                                                 |
| asyncio_tcp              | 526 ms                                                 | 487 ms: 1.08x faster                                                 |
| crypto_pyaes             | 77.2 ms                                                | 71.6 ms: 1.08x faster                                                |
| tomli_loads              | 2.22 sec                                               | 2.06 sec: 1.07x faster                                               |
| async_tree_none          | 469 ms                                                 | 438 ms: 1.07x faster                                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 66.5 ms: 1.07x faster                                                |
| unpickle                 | 15.0 us                                                | 14.1 us: 1.06x faster                                                |
| scimark_fft              | 358 ms                                                 | 340 ms: 1.05x faster                                                 |
| scimark_sor              | 125 ms                                                 | 119 ms: 1.05x faster                                                 |
| regex_effbot             | 3.55 ms                                                | 3.40 ms: 1.04x faster                                                |
| deltablue                | 3.52 ms                                                | 3.38 ms: 1.04x faster                                                |
| logging_simple           | 6.18 us                                                | 5.94 us: 1.04x faster                                                |
| logging_format           | 6.90 us                                                | 6.66 us: 1.04x faster                                                |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                                |
| sqlglot_transpile        | 1.64 ms                                                | 1.59 ms: 1.03x faster                                                |
| pickle_pure_python       | 309 us                                                 | 300 us: 1.03x faster                                                 |
| tornado_http             | 99.6 ms                                                | 96.8 ms: 1.03x faster                                                |
| coroutines               | 22.4 ms                                                | 21.8 ms: 1.03x faster                                                |
| pickle                   | 10.6 us                                                | 10.3 us: 1.03x faster                                                |
| pprint_safe_repr         | 735 ms                                                 | 717 ms: 1.03x faster                                                 |
| regex_dna                | 209 ms                                                 | 204 ms: 1.02x faster                                                 |
| xml_etree_process        | 58.6 ms                                                | 57.4 ms: 1.02x faster                                                |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 701 ms: 1.02x faster                                                 |
| xml_etree_generate       | 84.8 ms                                                | 83.4 ms: 1.02x faster                                                |
| pprint_pformat           | 1.50 sec                                               | 1.48 sec: 1.02x faster                                               |
| regex_compile            | 144 ms                                                 | 142 ms: 1.02x faster                                                 |
| unpickle_list            | 4.95 us                                                | 4.87 us: 1.01x faster                                                |
| pickle_dict              | 31.6 us                                                | 31.2 us: 1.01x faster                                                |
| deepcopy_reduce          | 3.14 us                                                | 3.10 us: 1.01x faster                                                |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                                |
| scimark_lu               | 114 ms                                                 | 112 ms: 1.01x faster                                                 |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.01x faster                                                 |
| docutils                 | 2.70 sec                                               | 2.67 sec: 1.01x faster                                               |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.69 ms: 1.01x faster                                                |
| deepcopy                 | 355 us                                                 | 351 us: 1.01x faster                                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.82 ms: 1.01x faster                                                |
| deepcopy_memo            | 37.4 us                                                | 37.0 us: 1.01x faster                                                |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                 |
| nbody                    | 88.8 ms                                                | 87.9 ms: 1.01x faster                                                |
| async_tree_memoization   | 573 ms                                                 | 567 ms: 1.01x faster                                                 |
| json_dumps               | 9.85 ms                                                | 9.77 ms: 1.01x faster                                                |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                 |
| gc_traversal             | 3.84 ms                                                | 3.84 ms: 1.00x slower                                                |
| pickle_list              | 4.62 us                                                | 4.64 us: 1.00x slower                                                |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.81 sec: 1.01x slower                                               |
| bench_thread_pool        | 827 us                                                 | 834 us: 1.01x slower                                                 |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                                 |
| float                    | 80.7 ms                                                | 81.5 ms: 1.01x slower                                                |
| typing_runtime_protocols | 146 us                                                 | 147 us: 1.01x slower                                                 |
| dulwich_log              | 67.9 ms                                                | 68.7 ms: 1.01x slower                                                |
| chaos                    | 63.5 ms                                                | 64.3 ms: 1.01x slower                                                |
| pyflate                  | 450 ms                                                 | 456 ms: 1.01x slower                                                 |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                |
| spectral_norm            | 106 ms                                                 | 108 ms: 1.02x slower                                                 |
| mypy2                    | 344 ms                                                 | 350 ms: 1.02x slower                                                 |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                               |
| unpickle_pure_python     | 218 us                                                 | 225 us: 1.03x slower                                                 |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.04x slower                                                 |
| async_generators         | 440 ms                                                 | 458 ms: 1.04x slower                                                 |
| meteor_contest           | 105 ms                                                 | 109 ms: 1.04x slower                                                 |
| unpack_sequence          | 44.8 ns                                                | 46.9 ns: 1.05x slower                                                |
| regex_v8                 | 22.3 ms                                                | 23.4 ms: 1.05x slower                                                |
| json                     | 4.77 ms                                                | 5.02 ms: 1.05x slower                                                |
| fannkuch                 | 387 ms                                                 | 409 ms: 1.06x slower                                                 |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                |
| mdp                      | 2.57 sec                                               | 2.73 sec: 1.06x slower                                               |
| go                       | 136 ms                                                 | 144 ms: 1.06x slower                                                 |
| nqueens                  | 81.1 ms                                                | 87.8 ms: 1.08x slower                                                |
| richards_super           | 49.0 ms                                                | 53.7 ms: 1.10x slower                                                |
| richards                 | 43.2 ms                                                | 47.6 ms: 1.10x slower                                                |
| comprehensions           | 20.4 us                                                | 22.5 us: 1.10x slower                                                |
| hexiom                   | 6.12 ms                                                | 6.80 ms: 1.11x slower                                                |
| telco                    | 6.87 ms                                                | 7.92 ms: 1.15x slower                                                |
| dask                     | 365 ms                                                 | 529 ms: 1.45x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.00x slower                                                         |

Benchmark hidden because not significant (5): sqlite_synth, pycparser, bench_mp_pool, sqlglot_optimize, json_loads
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 80.06% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
