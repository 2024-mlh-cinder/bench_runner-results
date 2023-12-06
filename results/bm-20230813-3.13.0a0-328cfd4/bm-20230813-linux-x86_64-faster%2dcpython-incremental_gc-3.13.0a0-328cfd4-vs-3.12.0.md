
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 328cfd4
- commit date: 2023-08-13
- overall geometric mean: 1.02x faster
- HPT reliability: 99.71%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-328cfd4 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.42 sec: 1.12x faster                                                    |
| tornado_http   | 99.6 ms                                                | 93.6 ms: 1.06x faster                                                     |
| Geometric mean | (ref)                                                  | 1.09x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-328cfd4 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 75.0 ms: 1.08x faster                                                     |
| pidigits       | 187 ms                                                 | 201 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                  | 1.00x faster                                                              |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-328cfd4 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| regex_v8       | 22.3 ms                                                | 22.1 ms: 1.01x faster                                                     |
| regex_effbot   | 3.55 ms                                                | 3.53 ms: 1.01x faster                                                     |
| regex_dna      | 209 ms                                                 | 213 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                  | 1.01x faster                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-328cfd4 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 299 us: 1.03x faster                                                      |
| xml_etree_iterparse  | 104 ms                                                 | 101 ms: 1.03x faster                                                      |
| unpickle_pure_python | 218 us                                                 | 213 us: 1.02x faster                                                      |
| pickle               | 10.6 us                                                | 10.4 us: 1.02x faster                                                     |
| json_dumps           | 9.85 ms                                                | 9.72 ms: 1.01x faster                                                     |
| xml_etree_process    | 58.6 ms                                                | 58.0 ms: 1.01x faster                                                     |
| xml_etree_generate   | 84.8 ms                                                | 84.1 ms: 1.01x faster                                                     |
| json_loads           | 25.2 us                                                | 25.6 us: 1.02x slower                                                     |
| pickle_dict          | 31.6 us                                                | 32.2 us: 1.02x slower                                                     |
| unpickle_list        | 4.95 us                                                | 5.16 us: 1.04x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.32 sec: 1.05x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.00x faster                                                              |

Benchmark hidden because not significant (3): xml_etree_parse, pickle_list, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-328cfd4 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.74 ms: 1.02x faster                                                     |
| python_startup         | 9.47 ms                                                | 9.27 ms: 1.02x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-328cfd4 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                     |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-328cfd4 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io            | 1.16 sec                                               | 676 ms: 1.71x faster                                                      |
| async_tree_none          | 469 ms                                                 | 308 ms: 1.52x faster                                                      |
| async_tree_memoization   | 573 ms                                                 | 393 ms: 1.46x faster                                                      |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 560 ms: 1.28x faster                                                      |
| docutils                 | 2.70 sec                                               | 2.42 sec: 1.12x faster                                                    |
| crypto_pyaes             | 77.2 ms                                                | 70.2 ms: 1.10x faster                                                     |
| deltablue                | 3.52 ms                                                | 3.20 ms: 1.10x faster                                                     |
| generators               | 31.1 ms                                                | 28.4 ms: 1.10x faster                                                     |
| raytrace                 | 294 ms                                                 | 272 ms: 1.08x faster                                                      |
| asyncio_tcp              | 526 ms                                                 | 487 ms: 1.08x faster                                                      |
| logging_format           | 6.90 us                                                | 6.41 us: 1.08x faster                                                     |
| float                    | 80.7 ms                                                | 75.0 ms: 1.08x faster                                                     |
| chaos                    | 63.5 ms                                                | 59.6 ms: 1.07x faster                                                     |
| tornado_http             | 99.6 ms                                                | 93.6 ms: 1.06x faster                                                     |
| logging_simple           | 6.18 us                                                | 5.84 us: 1.06x faster                                                     |
| regex_compile            | 144 ms                                                 | 137 ms: 1.05x faster                                                      |
| create_gc_cycles         | 1.52 ms                                                | 1.45 ms: 1.05x faster                                                     |
| scimark_monte_carlo      | 71.0 ms                                                | 68.2 ms: 1.04x faster                                                     |
| pickle_pure_python       | 309 us                                                 | 299 us: 1.03x faster                                                      |
| xml_etree_iterparse      | 104 ms                                                 | 101 ms: 1.03x faster                                                      |
| pycparser                | 1.15 sec                                               | 1.12 sec: 1.03x faster                                                    |
| sqlglot_parse            | 1.32 ms                                                | 1.29 ms: 1.03x faster                                                     |
| pprint_pformat           | 1.50 sec                                               | 1.46 sec: 1.02x faster                                                    |
| unpickle_pure_python     | 218 us                                                 | 213 us: 1.02x faster                                                      |
| python_startup_no_site   | 6.90 ms                                                | 6.74 ms: 1.02x faster                                                     |
| async_generators         | 440 ms                                                 | 430 ms: 1.02x faster                                                      |
| dulwich_log              | 67.9 ms                                                | 66.3 ms: 1.02x faster                                                     |
| pprint_safe_repr         | 735 ms                                                 | 718 ms: 1.02x faster                                                      |
| python_startup           | 9.47 ms                                                | 9.27 ms: 1.02x faster                                                     |
| scimark_sor              | 125 ms                                                 | 122 ms: 1.02x faster                                                      |
| sqlglot_transpile        | 1.64 ms                                                | 1.61 ms: 1.02x faster                                                     |
| coverage                 | 94.2 ms                                                | 92.5 ms: 1.02x faster                                                     |
| pickle                   | 10.6 us                                                | 10.4 us: 1.02x faster                                                     |
| gc_traversal             | 3.84 ms                                                | 3.79 ms: 1.01x faster                                                     |
| json_dumps               | 9.85 ms                                                | 9.72 ms: 1.01x faster                                                     |
| coroutines               | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                     |
| pyflate                  | 450 ms                                                 | 446 ms: 1.01x faster                                                      |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                      |
| xml_etree_process        | 58.6 ms                                                | 58.0 ms: 1.01x faster                                                     |
| regex_v8                 | 22.3 ms                                                | 22.1 ms: 1.01x faster                                                     |
| xml_etree_generate       | 84.8 ms                                                | 84.1 ms: 1.01x faster                                                     |
| spectral_norm            | 106 ms                                                 | 105 ms: 1.01x faster                                                      |
| typing_runtime_protocols | 146 us                                                 | 145 us: 1.01x faster                                                      |
| sqlglot_optimize         | 53.3 ms                                                | 53.0 ms: 1.01x faster                                                     |
| regex_effbot             | 3.55 ms                                                | 3.53 ms: 1.01x faster                                                     |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                    |
| mdp                      | 2.57 sec                                               | 2.56 sec: 1.00x faster                                                    |
| bench_thread_pool        | 827 us                                                 | 830 us: 1.00x slower                                                      |
| pathlib                  | 18.5 ms                                                | 18.6 ms: 1.00x slower                                                     |
| logging_silent           | 99.1 ns                                                | 99.7 ns: 1.01x slower                                                     |
| mypy2                    | 344 ms                                                 | 347 ms: 1.01x slower                                                      |
| hexiom                   | 6.12 ms                                                | 6.18 ms: 1.01x slower                                                     |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.80 ms: 1.01x slower                                                     |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.01x slower                                                     |
| json                     | 4.77 ms                                                | 4.83 ms: 1.01x slower                                                     |
| scimark_fft              | 358 ms                                                 | 364 ms: 1.01x slower                                                      |
| json_loads               | 25.2 us                                                | 25.6 us: 1.02x slower                                                     |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.02x slower                                                      |
| deepcopy_memo            | 37.4 us                                                | 38.0 us: 1.02x slower                                                     |
| unpack_sequence          | 44.8 ns                                                | 45.7 ns: 1.02x slower                                                     |
| pickle_dict              | 31.6 us                                                | 32.2 us: 1.02x slower                                                     |
| go                       | 136 ms                                                 | 138 ms: 1.02x slower                                                      |
| nqueens                  | 81.1 ms                                                | 82.7 ms: 1.02x slower                                                     |
| regex_dna                | 209 ms                                                 | 213 ms: 1.02x slower                                                      |
| fannkuch                 | 387 ms                                                 | 398 ms: 1.03x slower                                                      |
| deepcopy_reduce          | 3.14 us                                                | 3.23 us: 1.03x slower                                                     |
| unpickle_list            | 4.95 us                                                | 5.16 us: 1.04x slower                                                     |
| tomli_loads              | 2.22 sec                                               | 2.32 sec: 1.05x slower                                                    |
| richards_super           | 49.0 ms                                                | 52.5 ms: 1.07x slower                                                     |
| pidigits                 | 187 ms                                                 | 201 ms: 1.07x slower                                                      |
| richards                 | 43.2 ms                                                | 46.6 ms: 1.08x slower                                                     |
| telco                    | 6.87 ms                                                | 8.16 ms: 1.19x slower                                                     |
| dask                     | 365 ms                                                 | 492 ms: 1.35x slower                                                      |
| Geometric mean           | (ref)                                                  | 1.02x faster                                                              |

Benchmark hidden because not significant (9): xml_etree_parse, scimark_lu, nbody, bench_mp_pool, deepcopy, sqlite_synth, pickle_list, unpickle, comprehensions
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.71% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
