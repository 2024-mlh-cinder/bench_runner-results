
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_elf
- machine: linux-x86_64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.03x slower
- HPT reliability: 99.53%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.66 sec: 1.01x faster                                            |
| tornado_http   | 99.6 ms                                                | 96.7 ms: 1.03x faster                                             |
| Geometric mean | (ref)                                                  | 1.02x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.01x slower                                              |
| float          | 80.7 ms                                                | 84.0 ms: 1.04x slower                                             |
| nbody          | 88.8 ms                                                | 105 ms: 1.19x slower                                              |
| Geometric mean | (ref)                                                  | 1.08x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.39 ms: 1.05x faster                                             |
| regex_compile  | 144 ms                                                 | 143 ms: 1.01x faster                                              |
| regex_dna      | 209 ms                                                 | 210 ms: 1.01x slower                                              |
| regex_v8       | 22.3 ms                                                | 24.5 ms: 1.10x slower                                             |
| Geometric mean | (ref)                                                  | 1.01x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 297 us: 1.04x faster                                              |
| unpickle_list        | 4.95 us                                                | 4.86 us: 1.02x faster                                             |
| pickle               | 10.6 us                                                | 10.4 us: 1.01x faster                                             |
| xml_etree_process    | 58.6 ms                                                | 57.7 ms: 1.01x faster                                             |
| xml_etree_generate   | 84.8 ms                                                | 83.9 ms: 1.01x faster                                             |
| pickle_dict          | 31.6 us                                                | 31.9 us: 1.01x slower                                             |
| json_dumps           | 9.85 ms                                                | 9.94 ms: 1.01x slower                                             |
| xml_etree_iterparse  | 104 ms                                                 | 105 ms: 1.01x slower                                              |
| pickle_list          | 4.62 us                                                | 4.70 us: 1.02x slower                                             |
| unpickle_pure_python | 218 us                                                 | 225 us: 1.03x slower                                              |
| json_loads           | 25.2 us                                                | 26.1 us: 1.03x slower                                             |
| unpickle             | 15.0 us                                                | 16.5 us: 1.10x slower                                             |
| Geometric mean       | (ref)                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (2): tomli_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.92 ms: 1.00x slower                                             |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                             |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.1 ms: 1.03x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| coverage                 | 94.2 ms                                                | 85.3 ms: 1.10x faster                                             |
| generators               | 31.1 ms                                                | 28.5 ms: 1.09x faster                                             |
| crypto_pyaes             | 77.2 ms                                                | 70.9 ms: 1.09x faster                                             |
| regex_effbot             | 3.55 ms                                                | 3.39 ms: 1.05x faster                                             |
| pickle_pure_python       | 309 us                                                 | 297 us: 1.04x faster                                              |
| sqlglot_parse            | 1.32 ms                                                | 1.27 ms: 1.04x faster                                             |
| deepcopy_reduce          | 3.14 us                                                | 3.03 us: 1.04x faster                                             |
| logging_format           | 6.90 us                                                | 6.68 us: 1.03x faster                                             |
| asyncio_tcp              | 526 ms                                                 | 509 ms: 1.03x faster                                              |
| scimark_sor              | 125 ms                                                 | 121 ms: 1.03x faster                                              |
| tornado_http             | 99.6 ms                                                | 96.7 ms: 1.03x faster                                             |
| async_tree_none          | 469 ms                                                 | 457 ms: 1.03x faster                                              |
| sqlglot_transpile        | 1.64 ms                                                | 1.60 ms: 1.03x faster                                             |
| logging_simple           | 6.18 us                                                | 6.04 us: 1.02x faster                                             |
| raytrace                 | 294 ms                                                 | 289 ms: 1.02x faster                                              |
| unpickle_list            | 4.95 us                                                | 4.86 us: 1.02x faster                                             |
| deepcopy                 | 355 us                                                 | 349 us: 1.02x faster                                              |
| spectral_norm            | 106 ms                                                 | 104 ms: 1.02x faster                                              |
| pickle                   | 10.6 us                                                | 10.4 us: 1.01x faster                                             |
| xml_etree_process        | 58.6 ms                                                | 57.7 ms: 1.01x faster                                             |
| docutils                 | 2.70 sec                                               | 2.66 sec: 1.01x faster                                            |
| xml_etree_generate       | 84.8 ms                                                | 83.9 ms: 1.01x faster                                             |
| sqlite_synth             | 2.76 us                                                | 2.73 us: 1.01x faster                                             |
| regex_compile            | 144 ms                                                 | 143 ms: 1.01x faster                                              |
| sqlglot_normalize        | 107 ms                                                 | 107 ms: 1.01x faster                                              |
| scimark_fft              | 358 ms                                                 | 357 ms: 1.00x faster                                              |
| python_startup_no_site   | 6.90 ms                                                | 6.92 ms: 1.00x slower                                             |
| sqlglot_optimize         | 53.3 ms                                                | 53.6 ms: 1.01x slower                                             |
| coroutines               | 22.4 ms                                                | 22.6 ms: 1.01x slower                                             |
| regex_dna                | 209 ms                                                 | 210 ms: 1.01x slower                                              |
| pidigits                 | 187 ms                                                 | 188 ms: 1.01x slower                                              |
| pickle_dict              | 31.6 us                                                | 31.9 us: 1.01x slower                                             |
| json_dumps               | 9.85 ms                                                | 9.94 ms: 1.01x slower                                             |
| xml_etree_iterparse      | 104 ms                                                 | 105 ms: 1.01x slower                                              |
| typing_runtime_protocols | 146 us                                                 | 148 us: 1.01x slower                                              |
| create_gc_cycles         | 1.52 ms                                                | 1.54 ms: 1.01x slower                                             |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.82 sec: 1.01x slower                                            |
| mypy2                    | 344 ms                                                 | 349 ms: 1.02x slower                                              |
| bench_thread_pool        | 827 us                                                 | 841 us: 1.02x slower                                              |
| logging_silent           | 99.1 ns                                                | 101 ns: 1.02x slower                                              |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 727 ms: 1.02x slower                                              |
| pickle_list              | 4.62 us                                                | 4.70 us: 1.02x slower                                             |
| deltablue                | 3.52 ms                                                | 3.61 ms: 1.03x slower                                             |
| async_tree_memoization   | 573 ms                                                 | 589 ms: 1.03x slower                                              |
| scimark_monte_carlo      | 71.0 ms                                                | 73.0 ms: 1.03x slower                                             |
| json                     | 4.77 ms                                                | 4.91 ms: 1.03x slower                                             |
| unpickle_pure_python     | 218 us                                                 | 225 us: 1.03x slower                                              |
| mako                     | 10.7 ms                                                | 11.1 ms: 1.03x slower                                             |
| mdp                      | 2.57 sec                                               | 2.65 sec: 1.03x slower                                            |
| pathlib                  | 18.5 ms                                                | 19.1 ms: 1.03x slower                                             |
| json_loads               | 25.2 us                                                | 26.1 us: 1.03x slower                                             |
| deepcopy_memo            | 37.4 us                                                | 38.9 us: 1.04x slower                                             |
| async_generators         | 440 ms                                                 | 458 ms: 1.04x slower                                              |
| float                    | 80.7 ms                                                | 84.0 ms: 1.04x slower                                             |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 4.95 ms: 1.04x slower                                             |
| async_tree_io            | 1.16 sec                                               | 1.22 sec: 1.05x slower                                            |
| meteor_contest           | 105 ms                                                 | 111 ms: 1.06x slower                                              |
| pycparser                | 1.15 sec                                               | 1.22 sec: 1.07x slower                                            |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                             |
| fannkuch                 | 387 ms                                                 | 419 ms: 1.08x slower                                              |
| go                       | 136 ms                                                 | 147 ms: 1.09x slower                                              |
| richards_super           | 49.0 ms                                                | 53.3 ms: 1.09x slower                                             |
| regex_v8                 | 22.3 ms                                                | 24.5 ms: 1.10x slower                                             |
| unpickle                 | 15.0 us                                                | 16.5 us: 1.10x slower                                             |
| chaos                    | 63.5 ms                                                | 70.5 ms: 1.11x slower                                             |
| richards                 | 43.2 ms                                                | 48.0 ms: 1.11x slower                                             |
| pyflate                  | 450 ms                                                 | 502 ms: 1.12x slower                                              |
| gc_traversal             | 3.84 ms                                                | 4.36 ms: 1.14x slower                                             |
| unpack_sequence          | 44.8 ns                                                | 51.9 ns: 1.16x slower                                             |
| pprint_safe_repr         | 735 ms                                                 | 855 ms: 1.16x slower                                              |
| nqueens                  | 81.1 ms                                                | 94.6 ms: 1.17x slower                                             |
| nbody                    | 88.8 ms                                                | 105 ms: 1.19x slower                                              |
| comprehensions           | 20.4 us                                                | 24.3 us: 1.19x slower                                             |
| pprint_pformat           | 1.50 sec                                               | 1.79 sec: 1.19x slower                                            |
| telco                    | 6.87 ms                                                | 8.24 ms: 1.20x slower                                             |
| hexiom                   | 6.12 ms                                                | 7.71 ms: 1.26x slower                                             |
| Geometric mean           | (ref)                                                  | 1.03x slower                                                      |

Benchmark hidden because not significant (5): tomli_loads, xml_etree_parse, bench_mp_pool, dulwich_log, scimark_lu
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.53% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
