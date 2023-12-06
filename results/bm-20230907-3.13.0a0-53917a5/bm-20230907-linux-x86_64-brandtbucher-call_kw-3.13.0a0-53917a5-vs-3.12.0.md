
# Results vs. 3.12.0

- fork: brandtbucher
- ref: call_kw
- machine: linux-x86_64
- commit hash: 53917a5
- commit date: 2023-09-07
- overall geometric mean: 1.01x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.60 sec: 1.04x faster                                         |
| tornado_http   | 99.6 ms                                                | 94.7 ms: 1.05x faster                                          |
| Geometric mean | (ref)                                                  | 1.04x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 80.7 ms                                                | 78.9 ms: 1.02x faster                                          |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                           |
| Geometric mean | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 134 ms: 1.07x faster                                           |
| regex_effbot   | 3.55 ms                                                | 3.47 ms: 1.02x faster                                          |
| regex_v8       | 22.3 ms                                                | 23.6 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.06 sec: 1.08x faster                                         |
| pickle_pure_python   | 309 us                                                 | 300 us: 1.03x faster                                           |
| unpickle             | 15.0 us                                                | 14.6 us: 1.02x faster                                          |
| xml_etree_generate   | 84.8 ms                                                | 83.2 ms: 1.02x faster                                          |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.02x faster                                           |
| pickle_dict          | 31.6 us                                                | 31.1 us: 1.02x faster                                          |
| unpickle_list        | 4.95 us                                                | 4.87 us: 1.01x faster                                          |
| xml_etree_process    | 58.6 ms                                                | 57.7 ms: 1.01x faster                                          |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                           |
| unpickle_pure_python | 218 us                                                 | 216 us: 1.01x faster                                           |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                          |
| pickle_list          | 4.62 us                                                | 4.75 us: 1.03x slower                                          |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (2): json_loads, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.81 ms: 1.01x faster                                          |
| python_startup         | 9.47 ms                                                | 10.0 ms: 1.06x slower                                          |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.5 ms: 1.02x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230907-linux-x86_64-brandtbucher-call_kw-3.13.0a0-53917a5 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| crypto_pyaes             | 77.2 ms                                                | 68.3 ms: 1.13x faster                                          |
| coverage                 | 94.2 ms                                                | 85.6 ms: 1.10x faster                                          |
| raytrace                 | 294 ms                                                 | 268 ms: 1.10x faster                                           |
| asyncio_tcp              | 526 ms                                                 | 481 ms: 1.09x faster                                           |
| scimark_monte_carlo      | 71.0 ms                                                | 65.3 ms: 1.09x faster                                          |
| tomli_loads              | 2.22 sec                                               | 2.06 sec: 1.08x faster                                         |
| deltablue                | 3.52 ms                                                | 3.28 ms: 1.07x faster                                          |
| async_tree_none          | 469 ms                                                 | 438 ms: 1.07x faster                                           |
| regex_compile            | 144 ms                                                 | 134 ms: 1.07x faster                                           |
| generators               | 31.1 ms                                                | 29.3 ms: 1.06x faster                                          |
| logging_format           | 6.90 us                                                | 6.53 us: 1.06x faster                                          |
| logging_simple           | 6.18 us                                                | 5.86 us: 1.05x faster                                          |
| chaos                    | 63.5 ms                                                | 60.4 ms: 1.05x faster                                          |
| tornado_http             | 99.6 ms                                                | 94.7 ms: 1.05x faster                                          |
| unpack_sequence          | 44.8 ns                                                | 43.1 ns: 1.04x faster                                          |
| docutils                 | 2.70 sec                                               | 2.60 sec: 1.04x faster                                         |
| coroutines               | 22.4 ms                                                | 21.6 ms: 1.04x faster                                          |
| deepcopy                 | 355 us                                                 | 344 us: 1.03x faster                                           |
| sqlglot_parse            | 1.32 ms                                                | 1.28 ms: 1.03x faster                                          |
| scimark_sor              | 125 ms                                                 | 121 ms: 1.03x faster                                           |
| typing_runtime_protocols | 146 us                                                 | 141 us: 1.03x faster                                           |
| pickle_pure_python       | 309 us                                                 | 300 us: 1.03x faster                                           |
| nqueens                  | 81.1 ms                                                | 78.8 ms: 1.03x faster                                          |
| scimark_lu               | 114 ms                                                 | 111 ms: 1.03x faster                                           |
| dulwich_log              | 67.9 ms                                                | 66.1 ms: 1.03x faster                                          |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.03x faster                                          |
| bench_thread_pool        | 827 us                                                 | 806 us: 1.03x faster                                           |
| sqlglot_normalize        | 107 ms                                                 | 105 ms: 1.03x faster                                           |
| unpickle                 | 15.0 us                                                | 14.6 us: 1.02x faster                                          |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.63 ms: 1.02x faster                                          |
| deepcopy_memo            | 37.4 us                                                | 36.5 us: 1.02x faster                                          |
| fannkuch                 | 387 ms                                                 | 378 ms: 1.02x faster                                           |
| float                    | 80.7 ms                                                | 78.9 ms: 1.02x faster                                          |
| regex_effbot             | 3.55 ms                                                | 3.47 ms: 1.02x faster                                          |
| mako                     | 10.7 ms                                                | 10.5 ms: 1.02x faster                                          |
| mypy2                    | 344 ms                                                 | 337 ms: 1.02x faster                                           |
| xml_etree_generate       | 84.8 ms                                                | 83.2 ms: 1.02x faster                                          |
| async_tree_memoization   | 573 ms                                                 | 562 ms: 1.02x faster                                           |
| sqlglot_optimize         | 53.3 ms                                                | 52.3 ms: 1.02x faster                                          |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 701 ms: 1.02x faster                                           |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                           |
| hexiom                   | 6.12 ms                                                | 6.02 ms: 1.02x faster                                          |
| mdp                      | 2.57 sec                                               | 2.53 sec: 1.02x faster                                         |
| pickle_dict              | 31.6 us                                                | 31.1 us: 1.02x faster                                          |
| spectral_norm            | 106 ms                                                 | 105 ms: 1.02x faster                                           |
| unpickle_list            | 4.95 us                                                | 4.87 us: 1.01x faster                                          |
| xml_etree_process        | 58.6 ms                                                | 57.7 ms: 1.01x faster                                          |
| deepcopy_reduce          | 3.14 us                                                | 3.10 us: 1.01x faster                                          |
| scimark_fft              | 358 ms                                                 | 354 ms: 1.01x faster                                           |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                           |
| python_startup_no_site   | 6.90 ms                                                | 6.81 ms: 1.01x faster                                          |
| pprint_pformat           | 1.50 sec                                               | 1.48 sec: 1.01x faster                                         |
| unpickle_pure_python     | 218 us                                                 | 216 us: 1.01x faster                                           |
| pyflate                  | 450 ms                                                 | 447 ms: 1.01x faster                                           |
| pprint_safe_repr         | 735 ms                                                 | 730 ms: 1.01x faster                                           |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.80 sec: 1.00x slower                                         |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                           |
| meteor_contest           | 105 ms                                                 | 105 ms: 1.01x slower                                           |
| pathlib                  | 18.5 ms                                                | 18.6 ms: 1.01x slower                                          |
| comprehensions           | 20.4 us                                                | 20.7 us: 1.01x slower                                          |
| async_generators         | 440 ms                                                 | 446 ms: 1.01x slower                                           |
| go                       | 136 ms                                                 | 138 ms: 1.02x slower                                           |
| logging_silent           | 99.1 ns                                                | 101 ns: 1.02x slower                                           |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                          |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                         |
| pickle_list              | 4.62 us                                                | 4.75 us: 1.03x slower                                          |
| regex_v8                 | 22.3 ms                                                | 23.6 ms: 1.06x slower                                          |
| python_startup           | 9.47 ms                                                | 10.0 ms: 1.06x slower                                          |
| gc_traversal             | 3.84 ms                                                | 4.10 ms: 1.07x slower                                          |
| richards_super           | 49.0 ms                                                | 54.2 ms: 1.11x slower                                          |
| richards                 | 43.2 ms                                                | 48.6 ms: 1.13x slower                                          |
| telco                    | 6.87 ms                                                | 8.00 ms: 1.16x slower                                          |
| dask                     | 365 ms                                                 | 523 ms: 1.43x slower                                           |
| Geometric mean           | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (9): regex_dna, pycparser, create_gc_cycles, nbody, json_loads, bench_mp_pool, sqlite_synth, json, json_dumps
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
