
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_small
- machine: linux-x86_64
- commit hash: 1710e5b
- commit date: 2023-09-17
- overall geometric mean: 1.00x faster
- HPT reliability: 62.60%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.64 sec: 1.02x faster                                              |
| tornado_http   | 99.6 ms                                                | 96.0 ms: 1.04x faster                                               |
| Geometric mean | (ref)                                                  | 1.03x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 88.8 ms                                                | 83.7 ms: 1.06x faster                                               |
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                |
| float          | 80.7 ms                                                | 81.5 ms: 1.01x slower                                               |
| Geometric mean | (ref)                                                  | 1.02x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.34 ms: 1.06x faster                                               |
| regex_compile  | 144 ms                                                 | 138 ms: 1.04x faster                                                |
| regex_dna      | 209 ms                                                 | 204 ms: 1.02x faster                                                |
| regex_v8       | 22.3 ms                                                | 23.3 ms: 1.04x slower                                               |
| Geometric mean | (ref)                                                  | 1.02x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 1.98 sec: 1.12x faster                                              |
| pickle_pure_python   | 309 us                                                 | 298 us: 1.04x faster                                                |
| pickle_list          | 4.62 us                                                | 4.49 us: 1.03x faster                                               |
| xml_etree_process    | 58.6 ms                                                | 57.6 ms: 1.02x faster                                               |
| xml_etree_generate   | 84.8 ms                                                | 83.4 ms: 1.02x faster                                               |
| unpickle             | 15.0 us                                                | 14.8 us: 1.01x faster                                               |
| unpickle_list        | 4.95 us                                                | 4.91 us: 1.01x faster                                               |
| pickle_dict          | 31.6 us                                                | 31.6 us: 1.00x faster                                               |
| json_dumps           | 9.85 ms                                                | 9.91 ms: 1.01x slower                                               |
| unpickle_pure_python | 218 us                                                 | 221 us: 1.01x slower                                                |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                        |

Benchmark hidden because not significant (4): json_loads, xml_etree_iterparse, pickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.88 ms: 1.00x faster                                               |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                               |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.01x slower                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads             | 2.22 sec                                               | 1.98 sec: 1.12x faster                                              |
| raytrace                | 294 ms                                                 | 268 ms: 1.10x faster                                                |
| coverage                | 94.2 ms                                                | 86.4 ms: 1.09x faster                                               |
| scimark_fft             | 358 ms                                                 | 331 ms: 1.08x faster                                                |
| logging_format          | 6.90 us                                                | 6.45 us: 1.07x faster                                               |
| scimark_monte_carlo     | 71.0 ms                                                | 66.6 ms: 1.07x faster                                               |
| crypto_pyaes            | 77.2 ms                                                | 72.4 ms: 1.07x faster                                               |
| regex_effbot            | 3.55 ms                                                | 3.34 ms: 1.06x faster                                               |
| nbody                   | 88.8 ms                                                | 83.7 ms: 1.06x faster                                               |
| async_tree_none         | 469 ms                                                 | 443 ms: 1.06x faster                                                |
| unpack_sequence         | 44.8 ns                                                | 42.4 ns: 1.06x faster                                               |
| generators              | 31.1 ms                                                | 29.5 ms: 1.05x faster                                               |
| asyncio_tcp             | 526 ms                                                 | 501 ms: 1.05x faster                                                |
| deltablue               | 3.52 ms                                                | 3.36 ms: 1.05x faster                                               |
| logging_simple          | 6.18 us                                                | 5.92 us: 1.04x faster                                               |
| regex_compile           | 144 ms                                                 | 138 ms: 1.04x faster                                                |
| tornado_http            | 99.6 ms                                                | 96.0 ms: 1.04x faster                                               |
| scimark_sor             | 125 ms                                                 | 120 ms: 1.04x faster                                                |
| pickle_pure_python      | 309 us                                                 | 298 us: 1.04x faster                                                |
| sqlglot_parse           | 1.32 ms                                                | 1.28 ms: 1.03x faster                                               |
| chaos                   | 63.5 ms                                                | 61.7 ms: 1.03x faster                                               |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.61 ms: 1.03x faster                                               |
| sqlglot_transpile       | 1.64 ms                                                | 1.59 ms: 1.03x faster                                               |
| pickle_list             | 4.62 us                                                | 4.49 us: 1.03x faster                                               |
| docutils                | 2.70 sec                                               | 2.64 sec: 1.02x faster                                              |
| regex_dna               | 209 ms                                                 | 204 ms: 1.02x faster                                                |
| xml_etree_process       | 58.6 ms                                                | 57.6 ms: 1.02x faster                                               |
| xml_etree_generate      | 84.8 ms                                                | 83.4 ms: 1.02x faster                                               |
| async_tree_memoization  | 573 ms                                                 | 565 ms: 1.01x faster                                                |
| unpickle                | 15.0 us                                                | 14.8 us: 1.01x faster                                               |
| sqlglot_normalize       | 107 ms                                                 | 106 ms: 1.01x faster                                                |
| pprint_safe_repr        | 735 ms                                                 | 725 ms: 1.01x faster                                                |
| coroutines              | 22.4 ms                                                | 22.2 ms: 1.01x faster                                               |
| deepcopy                | 355 us                                                 | 352 us: 1.01x faster                                                |
| dulwich_log             | 67.9 ms                                                | 67.4 ms: 1.01x faster                                               |
| unpickle_list           | 4.95 us                                                | 4.91 us: 1.01x faster                                               |
| pprint_pformat          | 1.50 sec                                               | 1.49 sec: 1.01x faster                                              |
| python_startup_no_site  | 6.90 ms                                                | 6.88 ms: 1.00x faster                                               |
| pickle_dict             | 31.6 us                                                | 31.6 us: 1.00x faster                                               |
| create_gc_cycles        | 1.52 ms                                                | 1.53 ms: 1.00x slower                                               |
| mdp                     | 2.57 sec                                               | 2.58 sec: 1.00x slower                                              |
| pidigits                | 187 ms                                                 | 187 ms: 1.00x slower                                                |
| mypy2                   | 344 ms                                                 | 345 ms: 1.01x slower                                                |
| pycparser               | 1.15 sec                                               | 1.16 sec: 1.01x slower                                              |
| json_dumps              | 9.85 ms                                                | 9.91 ms: 1.01x slower                                               |
| float                   | 80.7 ms                                                | 81.5 ms: 1.01x slower                                               |
| mako                    | 10.7 ms                                                | 10.8 ms: 1.01x slower                                               |
| bench_thread_pool       | 827 us                                                 | 835 us: 1.01x slower                                                |
| deepcopy_memo           | 37.4 us                                                | 37.8 us: 1.01x slower                                               |
| asyncio_tcp_ssl         | 1.79 sec                                               | 1.81 sec: 1.01x slower                                              |
| unpickle_pure_python    | 218 us                                                 | 221 us: 1.01x slower                                                |
| pathlib                 | 18.5 ms                                                | 18.8 ms: 1.01x slower                                               |
| pyflate                 | 450 ms                                                 | 459 ms: 1.02x slower                                                |
| spectral_norm           | 106 ms                                                 | 108 ms: 1.02x slower                                                |
| meteor_contest          | 105 ms                                                 | 107 ms: 1.02x slower                                                |
| async_tree_io           | 1.16 sec                                               | 1.19 sec: 1.03x slower                                              |
| gc_traversal            | 3.84 ms                                                | 3.98 ms: 1.04x slower                                               |
| logging_silent          | 99.1 ns                                                | 103 ns: 1.04x slower                                                |
| regex_v8                | 22.3 ms                                                | 23.3 ms: 1.04x slower                                               |
| async_generators        | 440 ms                                                 | 459 ms: 1.04x slower                                                |
| fannkuch                | 387 ms                                                 | 406 ms: 1.05x slower                                                |
| nqueens                 | 81.1 ms                                                | 85.7 ms: 1.06x slower                                               |
| hexiom                  | 6.12 ms                                                | 6.53 ms: 1.07x slower                                               |
| python_startup          | 9.47 ms                                                | 10.1 ms: 1.07x slower                                               |
| go                      | 136 ms                                                 | 145 ms: 1.07x slower                                                |
| comprehensions          | 20.4 us                                                | 22.2 us: 1.09x slower                                               |
| richards                | 43.2 ms                                                | 46.9 ms: 1.09x slower                                               |
| richards_super          | 49.0 ms                                                | 54.0 ms: 1.10x slower                                               |
| telco                   | 6.87 ms                                                | 8.05 ms: 1.17x slower                                               |
| dask                    | 365 ms                                                 | 532 ms: 1.46x slower                                                |
| Geometric mean          | (ref)                                                  | 1.00x faster                                                        |

Benchmark hidden because not significant (12): scimark_lu, json_loads, xml_etree_iterparse, async_tree_cpu_io_mixed, sqlglot_optimize, sqlite_synth, bench_mp_pool, json, typing_runtime_protocols, pickle, deepcopy_reduce, xml_etree_parse
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 62.60% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
