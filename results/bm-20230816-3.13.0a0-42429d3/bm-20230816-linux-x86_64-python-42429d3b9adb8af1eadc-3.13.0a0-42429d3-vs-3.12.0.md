
# Results vs. 3.12.0

- fork: python
- ref: 42429d3b9adb8af1eadc
- machine: linux-x86_64
- commit hash: 42429d3
- commit date: 2023-08-16
- overall geometric mean: 1.00x slower
- HPT reliability: 98.43%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-python-42429d3b9adb8af1eadc-3.13.0a0-42429d3 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                |
| tornado_http   | 99.6 ms                                                | 95.3 ms: 1.05x faster                                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-python-42429d3b9adb8af1eadc-3.13.0a0-42429d3 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.8 ms                                                | 91.7 ms: 1.03x slower                                                 |
| pidigits       | 187 ms                                                 | 201 ms: 1.08x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                          |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-python-42429d3b9adb8af1eadc-3.13.0a0-42429d3 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                  |
| regex_v8       | 22.3 ms                                                | 22.9 ms: 1.03x slower                                                 |
| regex_effbot   | 3.55 ms                                                | 3.66 ms: 1.03x slower                                                 |
| regex_dna      | 209 ms                                                 | 217 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-python-42429d3b9adb8af1eadc-3.13.0a0-42429d3 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.11 sec: 1.05x faster                                                |
| pickle_pure_python   | 309 us                                                 | 298 us: 1.04x faster                                                  |
| unpickle_pure_python | 218 us                                                 | 213 us: 1.02x faster                                                  |
| json_dumps           | 9.85 ms                                                | 9.69 ms: 1.02x faster                                                 |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                  |
| unpickle             | 15.0 us                                                | 14.9 us: 1.01x faster                                                 |
| unpickle_list        | 4.95 us                                                | 4.92 us: 1.01x faster                                                 |
| pickle               | 10.6 us                                                | 10.8 us: 1.01x slower                                                 |
| pickle_dict          | 31.6 us                                                | 33.0 us: 1.04x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (5): xml_etree_parse, xml_etree_generate, xml_etree_process, json_loads, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-python-42429d3b9adb8af1eadc-3.13.0a0-42429d3 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.35 ms: 1.01x faster                                                 |
| python_startup_no_site | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-python-42429d3b9adb8af1eadc-3.13.0a0-42429d3 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230816-linux-x86_64-python-42429d3b9adb8af1eadc-3.13.0a0-42429d3 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 68.5 ms: 1.13x faster                                                 |
| coverage                 | 94.2 ms                                                | 85.1 ms: 1.11x faster                                                 |
| asyncio_tcp              | 526 ms                                                 | 486 ms: 1.08x faster                                                  |
| async_tree_none          | 469 ms                                                 | 435 ms: 1.08x faster                                                  |
| deltablue                | 3.52 ms                                                | 3.27 ms: 1.07x faster                                                 |
| scimark_monte_carlo      | 71.0 ms                                                | 66.2 ms: 1.07x faster                                                 |
| raytrace                 | 294 ms                                                 | 274 ms: 1.07x faster                                                  |
| generators               | 31.1 ms                                                | 29.0 ms: 1.07x faster                                                 |
| chaos                    | 63.5 ms                                                | 59.8 ms: 1.06x faster                                                 |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                  |
| tomli_loads              | 2.22 sec                                               | 2.11 sec: 1.05x faster                                                |
| logging_format           | 6.90 us                                                | 6.57 us: 1.05x faster                                                 |
| tornado_http             | 99.6 ms                                                | 95.3 ms: 1.05x faster                                                 |
| logging_simple           | 6.18 us                                                | 5.91 us: 1.04x faster                                                 |
| scimark_lu               | 114 ms                                                 | 109 ms: 1.04x faster                                                  |
| pickle_pure_python       | 309 us                                                 | 298 us: 1.04x faster                                                  |
| dulwich_log              | 67.9 ms                                                | 65.6 ms: 1.03x faster                                                 |
| docutils                 | 2.70 sec                                               | 2.62 sec: 1.03x faster                                                |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                                 |
| scimark_fft              | 358 ms                                                 | 349 ms: 1.03x faster                                                  |
| unpickle_pure_python     | 218 us                                                 | 213 us: 1.02x faster                                                  |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.02x faster                                                 |
| unpack_sequence          | 44.8 ns                                                | 43.9 ns: 1.02x faster                                                 |
| typing_runtime_protocols | 146 us                                                 | 143 us: 1.02x faster                                                  |
| create_gc_cycles         | 1.52 ms                                                | 1.49 ms: 1.02x faster                                                 |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 701 ms: 1.02x faster                                                  |
| async_tree_memoization   | 573 ms                                                 | 563 ms: 1.02x faster                                                  |
| json_dumps               | 9.85 ms                                                | 9.69 ms: 1.02x faster                                                 |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.02x faster                                                  |
| pyflate                  | 450 ms                                                 | 444 ms: 1.02x faster                                                  |
| python_startup           | 9.47 ms                                                | 9.35 ms: 1.01x faster                                                 |
| coroutines               | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                 |
| deepcopy                 | 355 us                                                 | 352 us: 1.01x faster                                                  |
| bench_thread_pool        | 827 us                                                 | 819 us: 1.01x faster                                                  |
| nqueens                  | 81.1 ms                                                | 80.3 ms: 1.01x faster                                                 |
| scimark_sor              | 125 ms                                                 | 123 ms: 1.01x faster                                                  |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                  |
| python_startup_no_site   | 6.90 ms                                                | 6.84 ms: 1.01x faster                                                 |
| unpickle                 | 15.0 us                                                | 14.9 us: 1.01x faster                                                 |
| hexiom                   | 6.12 ms                                                | 6.08 ms: 1.01x faster                                                 |
| pprint_pformat           | 1.50 sec                                               | 1.49 sec: 1.01x faster                                                |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                                 |
| spectral_norm            | 106 ms                                                 | 105 ms: 1.01x faster                                                  |
| unpickle_list            | 4.95 us                                                | 4.92 us: 1.01x faster                                                 |
| pprint_safe_repr         | 735 ms                                                 | 732 ms: 1.00x faster                                                  |
| sqlglot_optimize         | 53.3 ms                                                | 53.1 ms: 1.00x faster                                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                 |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                  |
| deepcopy_memo            | 37.4 us                                                | 37.7 us: 1.01x slower                                                 |
| deepcopy_reduce          | 3.14 us                                                | 3.17 us: 1.01x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 3.89 ms: 1.01x slower                                                 |
| fannkuch                 | 387 ms                                                 | 392 ms: 1.01x slower                                                  |
| pickle                   | 10.6 us                                                | 10.8 us: 1.01x slower                                                 |
| json                     | 4.77 ms                                                | 4.85 ms: 1.02x slower                                                 |
| comprehensions           | 20.4 us                                                | 20.8 us: 1.02x slower                                                 |
| go                       | 136 ms                                                 | 138 ms: 1.02x slower                                                  |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.85 ms: 1.02x slower                                                 |
| regex_v8                 | 22.3 ms                                                | 22.9 ms: 1.03x slower                                                 |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                |
| regex_effbot             | 3.55 ms                                                | 3.66 ms: 1.03x slower                                                 |
| nbody                    | 88.8 ms                                                | 91.7 ms: 1.03x slower                                                 |
| logging_silent           | 99.1 ns                                                | 102 ns: 1.03x slower                                                  |
| async_generators         | 440 ms                                                 | 457 ms: 1.04x slower                                                  |
| regex_dna                | 209 ms                                                 | 217 ms: 1.04x slower                                                  |
| pickle_dict              | 31.6 us                                                | 33.0 us: 1.04x slower                                                 |
| pycparser                | 1.15 sec                                               | 1.20 sec: 1.05x slower                                                |
| mdp                      | 2.57 sec                                               | 2.73 sec: 1.06x slower                                                |
| pidigits                 | 187 ms                                                 | 201 ms: 1.08x slower                                                  |
| richards                 | 43.2 ms                                                | 47.1 ms: 1.09x slower                                                 |
| richards_super           | 49.0 ms                                                | 54.2 ms: 1.11x slower                                                 |
| telco                    | 6.87 ms                                                | 8.05 ms: 1.17x slower                                                 |
| mypy2                    | 344 ms                                                 | 457 ms: 1.33x slower                                                  |
| dask                     | 365 ms                                                 | 520 ms: 1.43x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.00x slower                                                          |

Benchmark hidden because not significant (8): xml_etree_parse, xml_etree_generate, float, pathlib, xml_etree_process, bench_mp_pool, json_loads, pickle_list
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.43% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
