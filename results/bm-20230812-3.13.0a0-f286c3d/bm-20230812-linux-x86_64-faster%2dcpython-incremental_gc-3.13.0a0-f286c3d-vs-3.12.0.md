
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: f286c3d
- commit date: 2023-08-12
- overall geometric mean: 1.04x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-f286c3d |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.37 sec: 1.14x faster                                                    |
| tornado_http   | 99.6 ms                                                | 93.4 ms: 1.07x faster                                                     |
| Geometric mean | (ref)                                                  | 1.10x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-f286c3d |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 71.7 ms: 1.13x faster                                                     |
| nbody          | 88.8 ms                                                | 88.1 ms: 1.01x faster                                                     |
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| Geometric mean | (ref)                                                  | 1.04x faster                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-f286c3d |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| regex_effbot   | 3.55 ms                                                | 3.42 ms: 1.04x faster                                                     |
| regex_v8       | 22.3 ms                                                | 21.8 ms: 1.03x faster                                                     |
| Geometric mean | (ref)                                                  | 1.03x faster                                                              |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-f286c3d |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| xml_etree_iterparse  | 104 ms                                                 | 94.2 ms: 1.10x faster                                                     |
| xml_etree_parse      | 154 ms                                                 | 141 ms: 1.09x faster                                                      |
| pickle_pure_python   | 309 us                                                 | 295 us: 1.05x faster                                                      |
| xml_etree_generate   | 84.8 ms                                                | 81.3 ms: 1.04x faster                                                     |
| xml_etree_process    | 58.6 ms                                                | 56.9 ms: 1.03x faster                                                     |
| unpickle_pure_python | 218 us                                                 | 213 us: 1.02x faster                                                      |
| unpickle_list        | 4.95 us                                                | 4.92 us: 1.01x faster                                                     |
| pickle_list          | 4.62 us                                                | 4.64 us: 1.01x slower                                                     |
| json_loads           | 25.2 us                                                | 25.7 us: 1.02x slower                                                     |
| unpickle             | 15.0 us                                                | 15.4 us: 1.03x slower                                                     |
| pickle_dict          | 31.6 us                                                | 32.6 us: 1.03x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.34 sec: 1.06x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                              |

Benchmark hidden because not significant (2): json_dumps, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-f286c3d |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.27 ms: 1.02x faster                                                     |
| python_startup_no_site | 6.90 ms                                                | 6.79 ms: 1.02x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-f286c3d |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.00x slower                                                     |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-f286c3d |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io            | 1.16 sec                                               | 565 ms: 2.05x faster                                                      |
| async_tree_none          | 469 ms                                                 | 278 ms: 1.69x faster                                                      |
| async_tree_memoization   | 573 ms                                                 | 344 ms: 1.66x faster                                                      |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 506 ms: 1.41x faster                                                      |
| docutils                 | 2.70 sec                                               | 2.37 sec: 1.14x faster                                                    |
| gc_traversal             | 3.84 ms                                                | 3.40 ms: 1.13x faster                                                     |
| float                    | 80.7 ms                                                | 71.7 ms: 1.13x faster                                                     |
| crypto_pyaes             | 77.2 ms                                                | 69.0 ms: 1.12x faster                                                     |
| deltablue                | 3.52 ms                                                | 3.15 ms: 1.12x faster                                                     |
| xml_etree_iterparse      | 104 ms                                                 | 94.2 ms: 1.10x faster                                                     |
| xml_etree_parse          | 154 ms                                                 | 141 ms: 1.09x faster                                                      |
| raytrace                 | 294 ms                                                 | 270 ms: 1.09x faster                                                      |
| generators               | 31.1 ms                                                | 28.5 ms: 1.09x faster                                                     |
| asyncio_tcp              | 526 ms                                                 | 487 ms: 1.08x faster                                                      |
| create_gc_cycles         | 1.52 ms                                                | 1.41 ms: 1.08x faster                                                     |
| logging_format           | 6.90 us                                                | 6.44 us: 1.07x faster                                                     |
| chaos                    | 63.5 ms                                                | 59.5 ms: 1.07x faster                                                     |
| tornado_http             | 99.6 ms                                                | 93.4 ms: 1.07x faster                                                     |
| regex_compile            | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| scimark_monte_carlo      | 71.0 ms                                                | 67.4 ms: 1.05x faster                                                     |
| logging_simple           | 6.18 us                                                | 5.88 us: 1.05x faster                                                     |
| pickle_pure_python       | 309 us                                                 | 295 us: 1.05x faster                                                      |
| sqlglot_parse            | 1.32 ms                                                | 1.26 ms: 1.05x faster                                                     |
| xml_etree_generate       | 84.8 ms                                                | 81.3 ms: 1.04x faster                                                     |
| sqlglot_transpile        | 1.64 ms                                                | 1.58 ms: 1.04x faster                                                     |
| regex_effbot             | 3.55 ms                                                | 3.42 ms: 1.04x faster                                                     |
| async_generators         | 440 ms                                                 | 425 ms: 1.04x faster                                                      |
| scimark_sor              | 125 ms                                                 | 120 ms: 1.04x faster                                                      |
| xml_etree_process        | 58.6 ms                                                | 56.9 ms: 1.03x faster                                                     |
| pycparser                | 1.15 sec                                               | 1.12 sec: 1.03x faster                                                    |
| spectral_norm            | 106 ms                                                 | 103 ms: 1.03x faster                                                      |
| dulwich_log              | 67.9 ms                                                | 66.0 ms: 1.03x faster                                                     |
| regex_v8                 | 22.3 ms                                                | 21.8 ms: 1.03x faster                                                     |
| unpickle_pure_python     | 218 us                                                 | 213 us: 1.02x faster                                                      |
| python_startup           | 9.47 ms                                                | 9.27 ms: 1.02x faster                                                     |
| scimark_fft              | 358 ms                                                 | 352 ms: 1.02x faster                                                      |
| pprint_pformat           | 1.50 sec                                               | 1.48 sec: 1.02x faster                                                    |
| pprint_safe_repr         | 735 ms                                                 | 723 ms: 1.02x faster                                                      |
| python_startup_no_site   | 6.90 ms                                                | 6.79 ms: 1.02x faster                                                     |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.68 ms: 1.01x faster                                                     |
| mdp                      | 2.57 sec                                               | 2.53 sec: 1.01x faster                                                    |
| mypy2                    | 344 ms                                                 | 339 ms: 1.01x faster                                                      |
| coverage                 | 94.2 ms                                                | 93.0 ms: 1.01x faster                                                     |
| scimark_lu               | 114 ms                                                 | 113 ms: 1.01x faster                                                      |
| sqlglot_normalize        | 107 ms                                                 | 106 ms: 1.01x faster                                                      |
| deepcopy                 | 355 us                                                 | 352 us: 1.01x faster                                                      |
| comprehensions           | 20.4 us                                                | 20.3 us: 1.01x faster                                                     |
| nbody                    | 88.8 ms                                                | 88.1 ms: 1.01x faster                                                     |
| sqlglot_optimize         | 53.3 ms                                                | 52.9 ms: 1.01x faster                                                     |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                                                    |
| hexiom                   | 6.12 ms                                                | 6.08 ms: 1.01x faster                                                     |
| coroutines               | 22.4 ms                                                | 22.3 ms: 1.01x faster                                                     |
| unpickle_list            | 4.95 us                                                | 4.92 us: 1.01x faster                                                     |
| pathlib                  | 18.5 ms                                                | 18.4 ms: 1.01x faster                                                     |
| bench_thread_pool        | 827 us                                                 | 826 us: 1.00x faster                                                      |
| mako                     | 10.7 ms                                                | 10.8 ms: 1.00x slower                                                     |
| go                       | 136 ms                                                 | 136 ms: 1.00x slower                                                      |
| pickle_list              | 4.62 us                                                | 4.64 us: 1.01x slower                                                     |
| unpack_sequence          | 44.8 ns                                                | 45.1 ns: 1.01x slower                                                     |
| typing_runtime_protocols | 146 us                                                 | 147 us: 1.01x slower                                                      |
| deepcopy_reduce          | 3.14 us                                                | 3.16 us: 1.01x slower                                                     |
| meteor_contest           | 105 ms                                                 | 106 ms: 1.01x slower                                                      |
| nqueens                  | 81.1 ms                                                | 81.9 ms: 1.01x slower                                                     |
| fannkuch                 | 387 ms                                                 | 392 ms: 1.01x slower                                                      |
| sqlite_synth             | 2.76 us                                                | 2.79 us: 1.01x slower                                                     |
| pidigits                 | 187 ms                                                 | 189 ms: 1.01x slower                                                      |
| json                     | 4.77 ms                                                | 4.84 ms: 1.01x slower                                                     |
| json_loads               | 25.2 us                                                | 25.7 us: 1.02x slower                                                     |
| unpickle                 | 15.0 us                                                | 15.4 us: 1.03x slower                                                     |
| logging_silent           | 99.1 ns                                                | 102 ns: 1.03x slower                                                      |
| pickle_dict              | 31.6 us                                                | 32.6 us: 1.03x slower                                                     |
| tomli_loads              | 2.22 sec                                               | 2.34 sec: 1.06x slower                                                    |
| richards_super           | 49.0 ms                                                | 53.6 ms: 1.09x slower                                                     |
| richards                 | 43.2 ms                                                | 48.0 ms: 1.11x slower                                                     |
| telco                    | 6.87 ms                                                | 7.90 ms: 1.15x slower                                                     |
| dask                     | 365 ms                                                 | 485 ms: 1.33x slower                                                      |
| Geometric mean           | (ref)                                                  | 1.04x faster                                                              |

Benchmark hidden because not significant (6): pyflate, bench_mp_pool, deepcopy_memo, json_dumps, pickle, regex_dna
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
