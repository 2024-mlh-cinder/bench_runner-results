
# Results vs. base

- fork: brandtbucher
- ref: justin_opargs
- machine: linux-x86_64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.64 sec                                                              | 2.71 sec: 1.03x slower                                               |
| tornado_http   | 95.5 ms                                                               | 97.9 ms: 1.03x slower                                                |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 188 ms                                                                | 187 ms: 1.01x faster                                                 |
| float          | 78.8 ms                                                               | 83.3 ms: 1.06x slower                                                |
| nbody          | 89.1 ms                                                               | 99.8 ms: 1.12x slower                                                |
| Geometric mean | (ref)                                                                 | 1.06x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.77 ms                                                               | 3.63 ms: 1.04x faster                                                |
| regex_dna      | 219 ms                                                                | 222 ms: 1.01x slower                                                 |
| regex_v8       | 24.9 ms                                                               | 25.4 ms: 1.02x slower                                                |
| regex_compile  | 134 ms                                                                | 147 ms: 1.10x slower                                                 |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle             | 14.5 us                                                               | 13.9 us: 1.04x faster                                                |
| json_loads           | 25.1 us                                                               | 25.0 us: 1.01x faster                                                |
| pickle_dict          | 31.9 us                                                               | 31.7 us: 1.00x faster                                                |
| xml_etree_parse      | 150 ms                                                                | 152 ms: 1.01x slower                                                 |
| pickle_list          | 4.56 us                                                               | 4.62 us: 1.01x slower                                                |
| xml_etree_generate   | 81.6 ms                                                               | 83.3 ms: 1.02x slower                                                |
| xml_etree_iterparse  | 101 ms                                                                | 104 ms: 1.03x slower                                                 |
| json_dumps           | 9.67 ms                                                               | 9.96 ms: 1.03x slower                                                |
| xml_etree_process    | 56.3 ms                                                               | 58.3 ms: 1.04x slower                                                |
| pickle_pure_python   | 295 us                                                                | 306 us: 1.04x slower                                                 |
| pickle               | 10.2 us                                                               | 10.7 us: 1.05x slower                                                |
| unpickle_pure_python | 212 us                                                                | 228 us: 1.08x slower                                                 |
| tomli_loads          | 2.02 sec                                                              | 2.22 sec: 1.10x slower                                               |
| Geometric mean       | (ref)                                                                 | 1.02x slower                                                         |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 9.52 ms                                                               | 9.84 ms: 1.03x slower                                                |
| python_startup_no_site | 7.00 ms                                                               | 7.32 ms: 1.05x slower                                                |
| Geometric mean         | (ref)                                                                 | 1.04x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.7 ms                                                               | 11.7 ms: 1.09x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20230905-linux-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-linux-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| gc_traversal             | 4.09 ms                                                               | 3.84 ms: 1.06x faster                                                |
| regex_effbot             | 3.77 ms                                                               | 3.63 ms: 1.04x faster                                                |
| unpickle                 | 14.5 us                                                               | 13.9 us: 1.04x faster                                                |
| coroutines               | 22.9 ms                                                               | 22.1 ms: 1.03x faster                                                |
| deepcopy_reduce          | 3.13 us                                                               | 3.10 us: 1.01x faster                                                |
| pathlib                  | 19.0 ms                                                               | 18.8 ms: 1.01x faster                                                |
| pidigits                 | 188 ms                                                                | 187 ms: 1.01x faster                                                 |
| json_loads               | 25.1 us                                                               | 25.0 us: 1.01x faster                                                |
| pickle_dict              | 31.9 us                                                               | 31.7 us: 1.00x faster                                                |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.80 sec: 1.01x slower                                               |
| create_gc_cycles         | 1.49 ms                                                               | 1.50 ms: 1.01x slower                                                |
| xml_etree_parse          | 150 ms                                                                | 152 ms: 1.01x slower                                                 |
| unpack_sequence          | 46.4 ns                                                               | 46.9 ns: 1.01x slower                                                |
| richards_super           | 54.1 ms                                                               | 54.7 ms: 1.01x slower                                                |
| pickle_list              | 4.56 us                                                               | 4.62 us: 1.01x slower                                                |
| sqlglot_parse            | 1.28 ms                                                               | 1.30 ms: 1.01x slower                                                |
| regex_dna                | 219 ms                                                                | 222 ms: 1.01x slower                                                 |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.02x slower                                               |
| richards                 | 47.6 ms                                                               | 48.5 ms: 1.02x slower                                                |
| sqlglot_transpile        | 1.59 ms                                                               | 1.62 ms: 1.02x slower                                                |
| scimark_monte_carlo      | 67.5 ms                                                               | 68.8 ms: 1.02x slower                                                |
| regex_v8                 | 24.9 ms                                                               | 25.4 ms: 1.02x slower                                                |
| coverage                 | 85.3 ms                                                               | 87.0 ms: 1.02x slower                                                |
| dask                     | 522 ms                                                                | 532 ms: 1.02x slower                                                 |
| telco                    | 8.07 ms                                                               | 8.25 ms: 1.02x slower                                                |
| xml_etree_generate       | 81.6 ms                                                               | 83.3 ms: 1.02x slower                                                |
| logging_silent           | 103 ns                                                                | 105 ns: 1.02x slower                                                 |
| async_tree_cpu_io_mixed  | 698 ms                                                                | 714 ms: 1.02x slower                                                 |
| asyncio_tcp              | 480 ms                                                                | 491 ms: 1.02x slower                                                 |
| sqlglot_normalize        | 104 ms                                                                | 107 ms: 1.02x slower                                                 |
| generators               | 29.1 ms                                                               | 29.8 ms: 1.02x slower                                                |
| bench_thread_pool        | 819 us                                                                | 839 us: 1.03x slower                                                 |
| tornado_http             | 95.5 ms                                                               | 97.9 ms: 1.03x slower                                                |
| async_tree_memoization   | 563 ms                                                                | 578 ms: 1.03x slower                                                 |
| scimark_lu               | 112 ms                                                                | 114 ms: 1.03x slower                                                 |
| mdp                      | 2.56 sec                                                              | 2.63 sec: 1.03x slower                                               |
| pprint_safe_repr         | 729 ms                                                                | 748 ms: 1.03x slower                                                 |
| docutils                 | 2.64 sec                                                              | 2.71 sec: 1.03x slower                                               |
| xml_etree_iterparse      | 101 ms                                                                | 104 ms: 1.03x slower                                                 |
| sqlglot_optimize         | 52.6 ms                                                               | 54.1 ms: 1.03x slower                                                |
| deepcopy                 | 348 us                                                                | 358 us: 1.03x slower                                                 |
| json_dumps               | 9.67 ms                                                               | 9.96 ms: 1.03x slower                                                |
| python_startup           | 9.52 ms                                                               | 9.84 ms: 1.03x slower                                                |
| pprint_pformat           | 1.49 sec                                                              | 1.54 sec: 1.03x slower                                               |
| scimark_sor              | 119 ms                                                                | 123 ms: 1.03x slower                                                 |
| xml_etree_process        | 56.3 ms                                                               | 58.3 ms: 1.04x slower                                                |
| scimark_fft              | 360 ms                                                                | 373 ms: 1.04x slower                                                 |
| raytrace                 | 272 ms                                                                | 282 ms: 1.04x slower                                                 |
| pickle_pure_python       | 295 us                                                                | 306 us: 1.04x slower                                                 |
| dulwich_log              | 65.9 ms                                                               | 68.7 ms: 1.04x slower                                                |
| scimark_sparse_mat_mult  | 4.83 ms                                                               | 5.05 ms: 1.04x slower                                                |
| python_startup_no_site   | 7.00 ms                                                               | 7.32 ms: 1.05x slower                                                |
| mypy2                    | 338 ms                                                                | 355 ms: 1.05x slower                                                 |
| crypto_pyaes             | 68.4 ms                                                               | 72.0 ms: 1.05x slower                                                |
| spectral_norm            | 107 ms                                                                | 113 ms: 1.05x slower                                                 |
| pickle                   | 10.2 us                                                               | 10.7 us: 1.05x slower                                                |
| deepcopy_memo            | 36.6 us                                                               | 38.6 us: 1.06x slower                                                |
| async_generators         | 450 ms                                                                | 475 ms: 1.06x slower                                                 |
| float                    | 78.8 ms                                                               | 83.3 ms: 1.06x slower                                                |
| pycparser                | 1.15 sec                                                              | 1.22 sec: 1.06x slower                                               |
| go                       | 139 ms                                                                | 148 ms: 1.06x slower                                                 |
| deltablue                | 3.24 ms                                                               | 3.46 ms: 1.07x slower                                                |
| meteor_contest           | 106 ms                                                                | 113 ms: 1.07x slower                                                 |
| pyflate                  | 445 ms                                                                | 479 ms: 1.08x slower                                                 |
| unpickle_pure_python     | 212 us                                                                | 228 us: 1.08x slower                                                 |
| typing_runtime_protocols | 141 us                                                                | 153 us: 1.09x slower                                                 |
| mako                     | 10.7 ms                                                               | 11.7 ms: 1.09x slower                                                |
| tomli_loads              | 2.02 sec                                                              | 2.22 sec: 1.10x slower                                               |
| regex_compile            | 134 ms                                                                | 147 ms: 1.10x slower                                                 |
| chaos                    | 59.3 ms                                                               | 65.4 ms: 1.10x slower                                                |
| nbody                    | 89.1 ms                                                               | 99.8 ms: 1.12x slower                                                |
| fannkuch                 | 383 ms                                                                | 430 ms: 1.12x slower                                                 |
| nqueens                  | 81.8 ms                                                               | 93.7 ms: 1.14x slower                                                |
| comprehensions           | 20.5 us                                                               | 23.9 us: 1.17x slower                                                |
| hexiom                   | 5.95 ms                                                               | 7.13 ms: 1.20x slower                                                |
| Geometric mean           | (ref)                                                                 | 1.03x slower                                                         |

Benchmark hidden because not significant (7): json, sqlite_synth, unpickle_list, bench_mp_pool, logging_simple, logging_format, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
