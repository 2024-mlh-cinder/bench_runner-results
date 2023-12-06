
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 4591b30
- commit date: 2023-08-11
- overall geometric mean: 1.02x slower
- HPT reliability: 93.26%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4591b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.52 sec: 1.07x faster                                                    |
| tornado_http   | 99.6 ms                                                | 103 ms: 1.04x slower                                                      |
| Geometric mean | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4591b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| nbody          | 88.8 ms                                                | 90.0 ms: 1.01x slower                                                     |
| float          | 80.7 ms                                                | 110 ms: 1.37x slower                                                      |
| Geometric mean | (ref)                                                  | 1.12x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4591b30 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| regex_effbot   | 3.55 ms                                                | 3.59 ms: 1.01x slower                                                     |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                                      |
| Geometric mean | (ref)                                                  | 1.00x faster                                                              |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4591b30 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 294 us: 1.05x faster                                                      |
| unpickle_pure_python | 218 us                                                 | 213 us: 1.03x faster                                                      |
| pickle_list          | 4.62 us                                                | 4.54 us: 1.02x faster                                                     |
| unpickle_list        | 4.95 us                                                | 4.88 us: 1.01x faster                                                     |
| json_dumps           | 9.85 ms                                                | 9.75 ms: 1.01x faster                                                     |
| xml_etree_process    | 58.6 ms                                                | 58.3 ms: 1.00x faster                                                     |
| pickle               | 10.6 us                                                | 10.7 us: 1.01x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.29 sec: 1.03x slower                                                    |
| unpickle             | 15.0 us                                                | 15.6 us: 1.04x slower                                                     |
| xml_etree_generate   | 84.8 ms                                                | 93.5 ms: 1.10x slower                                                     |
| xml_etree_parse      | 154 ms                                                 | 570 ms: 3.71x slower                                                      |
| xml_etree_iterparse  | 104 ms                                                 | 516 ms: 4.98x slower                                                      |
| Geometric mean       | (ref)                                                  | 1.24x slower                                                              |

Benchmark hidden because not significant (2): pickle_dict, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4591b30 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.89 ms: 1.00x faster                                                     |
| python_startup         | 9.47 ms                                                | 9.47 ms: 1.00x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.00x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4591b30 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.01x slower                                                     |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230811-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4591b30 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io            | 1.16 sec                                               | 700 ms: 1.65x faster                                                      |
| async_tree_none          | 469 ms                                                 | 340 ms: 1.38x faster                                                      |
| async_tree_memoization   | 573 ms                                                 | 431 ms: 1.33x faster                                                      |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 586 ms: 1.22x faster                                                      |
| crypto_pyaes             | 77.2 ms                                                | 68.9 ms: 1.12x faster                                                     |
| unpack_sequence          | 44.8 ns                                                | 40.7 ns: 1.10x faster                                                     |
| asyncio_tcp              | 526 ms                                                 | 480 ms: 1.09x faster                                                      |
| chaos                    | 63.5 ms                                                | 58.4 ms: 1.09x faster                                                     |
| generators               | 31.1 ms                                                | 28.7 ms: 1.08x faster                                                     |
| raytrace                 | 294 ms                                                 | 272 ms: 1.08x faster                                                      |
| logging_format           | 6.90 us                                                | 6.43 us: 1.07x faster                                                     |
| docutils                 | 2.70 sec                                               | 2.52 sec: 1.07x faster                                                    |
| create_gc_cycles         | 1.52 ms                                                | 1.43 ms: 1.07x faster                                                     |
| deltablue                | 3.52 ms                                                | 3.33 ms: 1.06x faster                                                     |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| pickle_pure_python       | 309 us                                                 | 294 us: 1.05x faster                                                      |
| scimark_monte_carlo      | 71.0 ms                                                | 67.7 ms: 1.05x faster                                                     |
| gc_traversal             | 3.84 ms                                                | 3.68 ms: 1.05x faster                                                     |
| logging_simple           | 6.18 us                                                | 5.94 us: 1.04x faster                                                     |
| scimark_sor              | 125 ms                                                 | 120 ms: 1.04x faster                                                      |
| pprint_safe_repr         | 735 ms                                                 | 710 ms: 1.03x faster                                                      |
| pycparser                | 1.15 sec                                               | 1.11 sec: 1.03x faster                                                    |
| pprint_pformat           | 1.50 sec                                               | 1.46 sec: 1.03x faster                                                    |
| pyflate                  | 450 ms                                                 | 438 ms: 1.03x faster                                                      |
| unpickle_pure_python     | 218 us                                                 | 213 us: 1.03x faster                                                      |
| hexiom                   | 6.12 ms                                                | 5.98 ms: 1.02x faster                                                     |
| dulwich_log              | 67.9 ms                                                | 66.4 ms: 1.02x faster                                                     |
| nqueens                  | 81.1 ms                                                | 79.5 ms: 1.02x faster                                                     |
| coroutines               | 22.4 ms                                                | 22.0 ms: 1.02x faster                                                     |
| sqlglot_parse            | 1.32 ms                                                | 1.30 ms: 1.02x faster                                                     |
| spectral_norm            | 106 ms                                                 | 104 ms: 1.02x faster                                                      |
| pickle_list              | 4.62 us                                                | 4.54 us: 1.02x faster                                                     |
| unpickle_list            | 4.95 us                                                | 4.88 us: 1.01x faster                                                     |
| scimark_lu               | 114 ms                                                 | 113 ms: 1.01x faster                                                      |
| json_dumps               | 9.85 ms                                                | 9.75 ms: 1.01x faster                                                     |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                      |
| coverage                 | 94.2 ms                                                | 93.5 ms: 1.01x faster                                                     |
| sqlite_synth             | 2.76 us                                                | 2.74 us: 1.01x faster                                                     |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.01x faster                                                    |
| xml_etree_process        | 58.6 ms                                                | 58.3 ms: 1.00x faster                                                     |
| bench_thread_pool        | 827 us                                                 | 824 us: 1.00x faster                                                      |
| python_startup_no_site   | 6.90 ms                                                | 6.89 ms: 1.00x faster                                                     |
| python_startup           | 9.47 ms                                                | 9.47 ms: 1.00x faster                                                     |
| typing_runtime_protocols | 146 us                                                 | 147 us: 1.01x slower                                                      |
| scimark_fft              | 358 ms                                                 | 361 ms: 1.01x slower                                                      |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                      |
| sqlglot_optimize         | 53.3 ms                                                | 53.8 ms: 1.01x slower                                                     |
| pickle                   | 10.6 us                                                | 10.7 us: 1.01x slower                                                     |
| mdp                      | 2.57 sec                                               | 2.59 sec: 1.01x slower                                                    |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| mako                     | 10.7 ms                                                | 10.9 ms: 1.01x slower                                                     |
| pathlib                  | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                     |
| nbody                    | 88.8 ms                                                | 90.0 ms: 1.01x slower                                                     |
| regex_effbot             | 3.55 ms                                                | 3.59 ms: 1.01x slower                                                     |
| sqlglot_transpile        | 1.64 ms                                                | 1.66 ms: 1.01x slower                                                     |
| async_generators         | 440 ms                                                 | 447 ms: 1.02x slower                                                      |
| deepcopy_reduce          | 3.14 us                                                | 3.19 us: 1.02x slower                                                     |
| deepcopy_memo            | 37.4 us                                                | 38.1 us: 1.02x slower                                                     |
| go                       | 136 ms                                                 | 139 ms: 1.03x slower                                                      |
| regex_dna                | 209 ms                                                 | 215 ms: 1.03x slower                                                      |
| tomli_loads              | 2.22 sec                                               | 2.29 sec: 1.03x slower                                                    |
| logging_silent           | 99.1 ns                                                | 103 ns: 1.04x slower                                                      |
| tornado_http             | 99.6 ms                                                | 103 ms: 1.04x slower                                                      |
| unpickle                 | 15.0 us                                                | 15.6 us: 1.04x slower                                                     |
| richards                 | 43.2 ms                                                | 46.5 ms: 1.08x slower                                                     |
| richards_super           | 49.0 ms                                                | 53.3 ms: 1.09x slower                                                     |
| xml_etree_generate       | 84.8 ms                                                | 93.5 ms: 1.10x slower                                                     |
| telco                    | 6.87 ms                                                | 8.04 ms: 1.17x slower                                                     |
| mypy2                    | 344 ms                                                 | 444 ms: 1.29x slower                                                      |
| float                    | 80.7 ms                                                | 110 ms: 1.37x slower                                                      |
| dask                     | 365 ms                                                 | 520 ms: 1.43x slower                                                      |
| xml_etree_parse          | 154 ms                                                 | 570 ms: 3.71x slower                                                      |
| xml_etree_iterparse      | 104 ms                                                 | 516 ms: 4.98x slower                                                      |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                              |

Benchmark hidden because not significant (9): scimark_sparse_mat_mult, comprehensions, regex_v8, deepcopy, pickle_dict, bench_mp_pool, fannkuch, json_loads, json
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 93.26% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
