
# Results vs. 3.12.0

- fork: python
- ref: de5f8f7d13c0bbc723ea
- machine: linux-x86_64
- commit hash: de5f8f7
- commit date: 2023-09-11
- overall geometric mean: 1.01x faster
- HPT reliability: 99.95%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                |
| tornado_http   | 99.6 ms                                                | 95.5 ms: 1.04x faster                                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.9 ms: 1.01x faster                                                 |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                                          |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 133 ms: 1.08x faster                                                  |
| regex_effbot   | 3.55 ms                                                | 3.39 ms: 1.05x faster                                                 |
| regex_dna      | 209 ms                                                 | 205 ms: 1.02x faster                                                  |
| regex_v8       | 22.3 ms                                                | 23.7 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.02 sec: 1.10x faster                                                |
| pickle_pure_python   | 309 us                                                 | 297 us: 1.04x faster                                                  |
| unpickle             | 15.0 us                                                | 14.5 us: 1.03x faster                                                 |
| xml_etree_generate   | 84.8 ms                                                | 82.3 ms: 1.03x faster                                                 |
| xml_etree_process    | 58.6 ms                                                | 57.1 ms: 1.03x faster                                                 |
| unpickle_pure_python | 218 us                                                 | 214 us: 1.02x faster                                                  |
| xml_etree_parse      | 154 ms                                                 | 151 ms: 1.02x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                                  |
| pickle               | 10.6 us                                                | 10.5 us: 1.01x faster                                                 |
| json_dumps           | 9.85 ms                                                | 9.92 ms: 1.01x slower                                                 |
| pickle_dict          | 31.6 us                                                | 31.9 us: 1.01x slower                                                 |
| unpickle_list        | 4.95 us                                                | 5.05 us: 1.02x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                          |

Benchmark hidden because not significant (2): pickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.81 ms: 1.01x faster                                                 |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                          |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 68.7 ms: 1.12x faster                                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 64.6 ms: 1.10x faster                                                 |
| raytrace                 | 294 ms                                                 | 268 ms: 1.10x faster                                                  |
| tomli_loads              | 2.22 sec                                               | 2.02 sec: 1.10x faster                                                |
| generators               | 31.1 ms                                                | 28.6 ms: 1.09x faster                                                 |
| deltablue                | 3.52 ms                                                | 3.25 ms: 1.08x faster                                                 |
| asyncio_tcp              | 526 ms                                                 | 486 ms: 1.08x faster                                                  |
| regex_compile            | 144 ms                                                 | 133 ms: 1.08x faster                                                  |
| async_tree_none          | 469 ms                                                 | 437 ms: 1.07x faster                                                  |
| logging_format           | 6.90 us                                                | 6.45 us: 1.07x faster                                                 |
| coverage                 | 94.2 ms                                                | 88.4 ms: 1.06x faster                                                 |
| logging_simple           | 6.18 us                                                | 5.80 us: 1.06x faster                                                 |
| chaos                    | 63.5 ms                                                | 59.8 ms: 1.06x faster                                                 |
| hexiom                   | 6.12 ms                                                | 5.82 ms: 1.05x faster                                                 |
| scimark_sor              | 125 ms                                                 | 119 ms: 1.05x faster                                                  |
| sqlglot_parse            | 1.32 ms                                                | 1.26 ms: 1.05x faster                                                 |
| scimark_lu               | 114 ms                                                 | 109 ms: 1.05x faster                                                  |
| sqlglot_transpile        | 1.64 ms                                                | 1.57 ms: 1.05x faster                                                 |
| regex_effbot             | 3.55 ms                                                | 3.39 ms: 1.05x faster                                                 |
| coroutines               | 22.4 ms                                                | 21.5 ms: 1.04x faster                                                 |
| tornado_http             | 99.6 ms                                                | 95.5 ms: 1.04x faster                                                 |
| pickle_pure_python       | 309 us                                                 | 297 us: 1.04x faster                                                  |
| fannkuch                 | 387 ms                                                 | 373 ms: 1.04x faster                                                  |
| nqueens                  | 81.1 ms                                                | 78.4 ms: 1.03x faster                                                 |
| unpickle                 | 15.0 us                                                | 14.5 us: 1.03x faster                                                 |
| docutils                 | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                |
| sqlglot_normalize        | 107 ms                                                 | 104 ms: 1.03x faster                                                  |
| xml_etree_generate       | 84.8 ms                                                | 82.3 ms: 1.03x faster                                                 |
| spectral_norm            | 106 ms                                                 | 103 ms: 1.03x faster                                                  |
| deepcopy_memo            | 37.4 us                                                | 36.4 us: 1.03x faster                                                 |
| typing_runtime_protocols | 146 us                                                 | 142 us: 1.03x faster                                                  |
| xml_etree_process        | 58.6 ms                                                | 57.1 ms: 1.03x faster                                                 |
| scimark_fft              | 358 ms                                                 | 350 ms: 1.02x faster                                                  |
| unpickle_pure_python     | 218 us                                                 | 214 us: 1.02x faster                                                  |
| bench_thread_pool        | 827 us                                                 | 809 us: 1.02x faster                                                  |
| dulwich_log              | 67.9 ms                                                | 66.5 ms: 1.02x faster                                                 |
| mypy2                    | 344 ms                                                 | 337 ms: 1.02x faster                                                  |
| regex_dna                | 209 ms                                                 | 205 ms: 1.02x faster                                                  |
| sqlglot_optimize         | 53.3 ms                                                | 52.3 ms: 1.02x faster                                                 |
| deepcopy                 | 355 us                                                 | 349 us: 1.02x faster                                                  |
| xml_etree_parse          | 154 ms                                                 | 151 ms: 1.02x faster                                                  |
| pyflate                  | 450 ms                                                 | 443 ms: 1.02x faster                                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.67 ms: 1.02x faster                                                 |
| async_tree_memoization   | 573 ms                                                 | 564 ms: 1.02x faster                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                                  |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 705 ms: 1.01x faster                                                  |
| python_startup_no_site   | 6.90 ms                                                | 6.81 ms: 1.01x faster                                                 |
| pathlib                  | 18.5 ms                                                | 18.3 ms: 1.01x faster                                                 |
| unpack_sequence          | 44.8 ns                                                | 44.4 ns: 1.01x faster                                                 |
| float                    | 80.7 ms                                                | 79.9 ms: 1.01x faster                                                 |
| pickle                   | 10.6 us                                                | 10.5 us: 1.01x faster                                                 |
| pycparser                | 1.15 sec                                               | 1.14 sec: 1.01x faster                                                |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                                  |
| meteor_contest           | 105 ms                                                 | 105 ms: 1.00x slower                                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.53 ms: 1.01x slower                                                 |
| json_dumps               | 9.85 ms                                                | 9.92 ms: 1.01x slower                                                 |
| pickle_dict              | 31.6 us                                                | 31.9 us: 1.01x slower                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.52 sec: 1.01x slower                                                |
| async_generators         | 440 ms                                                 | 447 ms: 1.01x slower                                                  |
| go                       | 136 ms                                                 | 138 ms: 1.01x slower                                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.18 us: 1.01x slower                                                 |
| sqlite_synth             | 2.76 us                                                | 2.80 us: 1.02x slower                                                 |
| unpickle_list            | 4.95 us                                                | 5.05 us: 1.02x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                |
| gc_traversal             | 3.84 ms                                                | 3.98 ms: 1.04x slower                                                 |
| mdp                      | 2.57 sec                                               | 2.69 sec: 1.05x slower                                                |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                                 |
| regex_v8                 | 22.3 ms                                                | 23.7 ms: 1.06x slower                                                 |
| richards_super           | 49.0 ms                                                | 53.1 ms: 1.09x slower                                                 |
| richards                 | 43.2 ms                                                | 47.0 ms: 1.09x slower                                                 |
| telco                    | 6.87 ms                                                | 8.04 ms: 1.17x slower                                                 |
| dask                     | 365 ms                                                 | 522 ms: 1.43x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (9): json, logging_silent, mako, bench_mp_pool, comprehensions, pprint_safe_repr, pickle_list, json_loads, nbody
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.95% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
