
# Results vs. 3.12.0

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: linux-x86_64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.01x faster
- HPT reliability: 99.31%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.60 sec: 1.04x faster                                                |
| tornado_http   | 99.6 ms                                                | 95.2 ms: 1.05x faster                                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 79.5 ms: 1.02x faster                                                 |
| nbody          | 88.8 ms                                                | 88.1 ms: 1.01x faster                                                 |
| pidigits       | 187 ms                                                 | 212 ms: 1.14x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 134 ms: 1.08x faster                                                  |
| regex_effbot   | 3.55 ms                                                | 3.42 ms: 1.04x faster                                                 |
| regex_dna      | 209 ms                                                 | 205 ms: 1.02x faster                                                  |
| regex_v8       | 22.3 ms                                                | 23.6 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 1.99 sec: 1.11x faster                                                |
| pickle_pure_python   | 309 us                                                 | 297 us: 1.04x faster                                                  |
| unpickle_pure_python | 218 us                                                 | 212 us: 1.03x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 101 ms: 1.02x faster                                                  |
| xml_etree_process    | 58.6 ms                                                | 57.7 ms: 1.01x faster                                                 |
| xml_etree_generate   | 84.8 ms                                                | 83.8 ms: 1.01x faster                                                 |
| unpickle_list        | 4.95 us                                                | 4.90 us: 1.01x faster                                                 |
| json_loads           | 25.2 us                                                | 25.1 us: 1.01x faster                                                 |
| pickle               | 10.6 us                                                | 10.9 us: 1.02x slower                                                 |
| pickle_list          | 4.62 us                                                | 4.74 us: 1.03x slower                                                 |
| pickle_dict          | 31.6 us                                                | 32.7 us: 1.03x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (3): xml_etree_parse, json_dumps, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                 |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.6 ms: 1.01x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 68.5 ms: 1.13x faster                                                 |
| tomli_loads              | 2.22 sec                                               | 1.99 sec: 1.11x faster                                                |
| generators               | 31.1 ms                                                | 28.0 ms: 1.11x faster                                                 |
| raytrace                 | 294 ms                                                 | 268 ms: 1.10x faster                                                  |
| unpack_sequence          | 44.8 ns                                                | 41.1 ns: 1.09x faster                                                 |
| coverage                 | 94.2 ms                                                | 86.7 ms: 1.09x faster                                                 |
| asyncio_tcp              | 526 ms                                                 | 488 ms: 1.08x faster                                                  |
| logging_format           | 6.90 us                                                | 6.42 us: 1.08x faster                                                 |
| regex_compile            | 144 ms                                                 | 134 ms: 1.08x faster                                                  |
| scimark_monte_carlo      | 71.0 ms                                                | 66.4 ms: 1.07x faster                                                 |
| async_tree_none          | 469 ms                                                 | 439 ms: 1.07x faster                                                  |
| chaos                    | 63.5 ms                                                | 59.9 ms: 1.06x faster                                                 |
| deltablue                | 3.52 ms                                                | 3.32 ms: 1.06x faster                                                 |
| logging_simple           | 6.18 us                                                | 5.83 us: 1.06x faster                                                 |
| deepcopy_memo            | 37.4 us                                                | 35.6 us: 1.05x faster                                                 |
| tornado_http             | 99.6 ms                                                | 95.2 ms: 1.05x faster                                                 |
| pickle_pure_python       | 309 us                                                 | 297 us: 1.04x faster                                                  |
| docutils                 | 2.70 sec                                               | 2.60 sec: 1.04x faster                                                |
| regex_effbot             | 3.55 ms                                                | 3.42 ms: 1.04x faster                                                 |
| sqlglot_transpile        | 1.64 ms                                                | 1.58 ms: 1.04x faster                                                 |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.04x faster                                                 |
| nqueens                  | 81.1 ms                                                | 78.3 ms: 1.04x faster                                                 |
| hexiom                   | 6.12 ms                                                | 5.91 ms: 1.04x faster                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.45 sec: 1.04x faster                                                |
| scimark_lu               | 114 ms                                                 | 111 ms: 1.03x faster                                                  |
| sqlglot_normalize        | 107 ms                                                 | 104 ms: 1.03x faster                                                  |
| unpickle_pure_python     | 218 us                                                 | 212 us: 1.03x faster                                                  |
| pprint_safe_repr         | 735 ms                                                 | 715 ms: 1.03x faster                                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.62 ms: 1.03x faster                                                 |
| dulwich_log              | 67.9 ms                                                | 66.2 ms: 1.03x faster                                                 |
| bench_thread_pool        | 827 us                                                 | 807 us: 1.02x faster                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 101 ms: 1.02x faster                                                  |
| coroutines               | 22.4 ms                                                | 21.9 ms: 1.02x faster                                                 |
| spectral_norm            | 106 ms                                                 | 104 ms: 1.02x faster                                                  |
| sqlglot_optimize         | 53.3 ms                                                | 52.2 ms: 1.02x faster                                                 |
| mypy2                    | 344 ms                                                 | 337 ms: 1.02x faster                                                  |
| deepcopy                 | 355 us                                                 | 348 us: 1.02x faster                                                  |
| regex_dna                | 209 ms                                                 | 205 ms: 1.02x faster                                                  |
| typing_runtime_protocols | 146 us                                                 | 144 us: 1.02x faster                                                  |
| float                    | 80.7 ms                                                | 79.5 ms: 1.02x faster                                                 |
| mdp                      | 2.57 sec                                               | 2.53 sec: 1.02x faster                                                |
| xml_etree_process        | 58.6 ms                                                | 57.7 ms: 1.01x faster                                                 |
| xml_etree_generate       | 84.8 ms                                                | 83.8 ms: 1.01x faster                                                 |
| comprehensions           | 20.4 us                                                | 20.2 us: 1.01x faster                                                 |
| fannkuch                 | 387 ms                                                 | 383 ms: 1.01x faster                                                  |
| unpickle_list            | 4.95 us                                                | 4.90 us: 1.01x faster                                                 |
| mako                     | 10.7 ms                                                | 10.6 ms: 1.01x faster                                                 |
| nbody                    | 88.8 ms                                                | 88.1 ms: 1.01x faster                                                 |
| json_loads               | 25.2 us                                                | 25.1 us: 1.01x faster                                                 |
| pathlib                  | 18.5 ms                                                | 18.4 ms: 1.01x faster                                                 |
| python_startup_no_site   | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                                |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                 |
| async_generators         | 440 ms                                                 | 444 ms: 1.01x slower                                                  |
| pyflate                  | 450 ms                                                 | 456 ms: 1.01x slower                                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.54 ms: 1.01x slower                                                 |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                  |
| pickle                   | 10.6 us                                                | 10.9 us: 1.02x slower                                                 |
| pickle_list              | 4.62 us                                                | 4.74 us: 1.03x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.20 sec: 1.03x slower                                                |
| pickle_dict              | 31.6 us                                                | 32.7 us: 1.03x slower                                                 |
| go                       | 136 ms                                                 | 141 ms: 1.04x slower                                                  |
| scimark_sor              | 125 ms                                                 | 130 ms: 1.05x slower                                                  |
| regex_v8                 | 22.3 ms                                                | 23.6 ms: 1.05x slower                                                 |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                 |
| richards_super           | 49.0 ms                                                | 53.5 ms: 1.09x slower                                                 |
| richards                 | 43.2 ms                                                | 47.7 ms: 1.10x slower                                                 |
| pidigits                 | 187 ms                                                 | 212 ms: 1.14x slower                                                  |
| telco                    | 6.87 ms                                                | 8.03 ms: 1.17x slower                                                 |
| dask                     | 365 ms                                                 | 529 ms: 1.45x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (12): async_tree_memoization, async_tree_cpu_io_mixed, logging_silent, deepcopy_reduce, sqlite_synth, bench_mp_pool, xml_etree_parse, json_dumps, json, unpickle, pycparser, scimark_fft
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.31% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
