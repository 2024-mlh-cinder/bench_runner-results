
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_elf
- machine: darwin-arm64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.01x slower
- HPT reliability: 99.24%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.52 sec: 1.01x faster                                            |
| Geometric mean | (ref)                                                  | 1.01x faster                                                      |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| float          | 58.2 ms                                                | 57.0 ms: 1.02x faster                                             |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                              |
| nbody          | 68.6 ms                                                | 79.6 ms: 1.16x slower                                             |
| Geometric mean | (ref)                                                  | 1.04x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 140 ms: 1.07x faster                                              |
| regex_effbot   | 2.58 ms                                                | 2.54 ms: 1.01x faster                                             |
| regex_v8       | 16.0 ms                                                | 16.4 ms: 1.03x slower                                             |
| regex_compile  | 75.8 ms                                                | 81.3 ms: 1.07x slower                                             |
| Geometric mean | (ref)                                                  | 1.00x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.85 us: 1.03x faster                                             |
| unpickle_list        | 3.22 us                                                | 3.16 us: 1.02x faster                                             |
| unpickle             | 9.26 us                                                | 9.17 us: 1.01x faster                                             |
| json_loads           | 17.6 us                                                | 17.7 us: 1.01x slower                                             |
| json_dumps           | 6.43 ms                                                | 6.53 ms: 1.02x slower                                             |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                              |
| xml_etree_process    | 38.5 ms                                                | 39.6 ms: 1.03x slower                                             |
| xml_etree_iterparse  | 74.3 ms                                                | 76.5 ms: 1.03x slower                                             |
| xml_etree_generate   | 55.8 ms                                                | 57.7 ms: 1.03x slower                                             |
| pickle_pure_python   | 188 us                                                 | 197 us: 1.05x slower                                              |
| unpickle_pure_python | 145 us                                                 | 160 us: 1.11x slower                                              |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                      |

Benchmark hidden because not significant (3): tomli_loads, pickle_dict, pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 8.62 ms: 1.09x faster                                             |
| python_startup         | 11.5 ms                                                | 11.2 ms: 1.03x faster                                             |
| Geometric mean         | (ref)                                                  | 1.06x faster                                                      |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 185 ms: 1.33x faster                                              |
| generators               | 28.5 ms                                                | 25.1 ms: 1.13x faster                                             |
| sqlglot_parse            | 898 us                                                 | 813 us: 1.10x faster                                              |
| python_startup_no_site   | 9.43 ms                                                | 8.62 ms: 1.09x faster                                             |
| asyncio_tcp              | 460 ms                                                 | 421 ms: 1.09x faster                                              |
| coverage                 | 51.0 ms                                                | 46.9 ms: 1.09x faster                                             |
| sqlglot_transpile        | 1.07 ms                                                | 990 us: 1.08x faster                                              |
| regex_dna                | 151 ms                                                 | 140 ms: 1.07x faster                                              |
| crypto_pyaes             | 52.3 ms                                                | 48.7 ms: 1.07x faster                                             |
| scimark_monte_carlo      | 50.1 ms                                                | 47.3 ms: 1.06x faster                                             |
| unpack_sequence          | 28.8 ns                                                | 27.3 ns: 1.05x faster                                             |
| python_startup           | 11.5 ms                                                | 11.2 ms: 1.03x faster                                             |
| chaos                    | 45.2 ms                                                | 43.9 ms: 1.03x faster                                             |
| pickle_list              | 2.92 us                                                | 2.85 us: 1.03x faster                                             |
| spectral_norm            | 75.0 ms                                                | 73.0 ms: 1.03x faster                                             |
| deltablue                | 2.59 ms                                                | 2.53 ms: 1.03x faster                                             |
| async_tree_none          | 262 ms                                                 | 255 ms: 1.03x faster                                              |
| logging_simple           | 3.69 us                                                | 3.62 us: 1.02x faster                                             |
| float                    | 58.2 ms                                                | 57.0 ms: 1.02x faster                                             |
| json                     | 3.05 ms                                                | 2.99 ms: 1.02x faster                                             |
| unpickle_list            | 3.22 us                                                | 3.16 us: 1.02x faster                                             |
| logging_format           | 3.97 us                                                | 3.91 us: 1.02x faster                                             |
| regex_effbot             | 2.58 ms                                                | 2.54 ms: 1.01x faster                                             |
| coroutines               | 18.2 ms                                                | 18.0 ms: 1.01x faster                                             |
| docutils                 | 1.54 sec                                               | 1.52 sec: 1.01x faster                                            |
| unpickle                 | 9.26 us                                                | 9.17 us: 1.01x faster                                             |
| deepcopy_reduce          | 2.02 us                                                | 2.00 us: 1.01x faster                                             |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                              |
| sqlglot_normalize        | 186 ms                                                 | 186 ms: 1.00x slower                                              |
| gc_traversal             | 2.40 ms                                                | 2.41 ms: 1.00x slower                                             |
| json_loads               | 17.6 us                                                | 17.7 us: 1.01x slower                                             |
| create_gc_cycles         | 702 us                                                 | 708 us: 1.01x slower                                              |
| go                       | 107 ms                                                 | 108 ms: 1.01x slower                                              |
| bench_thread_pool        | 489 us                                                 | 494 us: 1.01x slower                                              |
| deepcopy                 | 224 us                                                 | 226 us: 1.01x slower                                              |
| sqlglot_optimize         | 34.3 ms                                                | 34.8 ms: 1.02x slower                                             |
| bench_mp_pool            | 45.9 ms                                                | 46.6 ms: 1.02x slower                                             |
| json_dumps               | 6.43 ms                                                | 6.53 ms: 1.02x slower                                             |
| xml_etree_parse          | 109 ms                                                 | 111 ms: 1.02x slower                                              |
| richards_super           | 34.9 ms                                                | 35.6 ms: 1.02x slower                                             |
| pyflate                  | 329 ms                                                 | 337 ms: 1.02x slower                                              |
| scimark_lu               | 71.7 ms                                                | 73.4 ms: 1.02x slower                                             |
| dulwich_log              | 30.3 ms                                                | 31.1 ms: 1.02x slower                                             |
| async_generators         | 303 ms                                                 | 311 ms: 1.03x slower                                              |
| xml_etree_process        | 38.5 ms                                                | 39.6 ms: 1.03x slower                                             |
| regex_v8                 | 16.0 ms                                                | 16.4 ms: 1.03x slower                                             |
| richards                 | 31.1 ms                                                | 31.9 ms: 1.03x slower                                             |
| xml_etree_iterparse      | 74.3 ms                                                | 76.5 ms: 1.03x slower                                             |
| sqlite_synth             | 1.58 us                                                | 1.63 us: 1.03x slower                                             |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.26 ms: 1.03x slower                                             |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.30 sec: 1.03x slower                                            |
| xml_etree_generate       | 55.8 ms                                                | 57.7 ms: 1.03x slower                                             |
| pycparser                | 670 ms                                                 | 698 ms: 1.04x slower                                              |
| typing_runtime_protocols | 90.7 us                                                | 94.6 us: 1.04x slower                                             |
| pickle_pure_python       | 188 us                                                 | 197 us: 1.05x slower                                              |
| deepcopy_memo            | 24.5 us                                                | 25.6 us: 1.05x slower                                             |
| comprehensions           | 15.7 us                                                | 16.5 us: 1.05x slower                                             |
| async_tree_io            | 669 ms                                                 | 705 ms: 1.05x slower                                              |
| nqueens                  | 60.6 ms                                                | 64.0 ms: 1.06x slower                                             |
| meteor_contest           | 72.9 ms                                                | 78.1 ms: 1.07x slower                                             |
| regex_compile            | 75.8 ms                                                | 81.3 ms: 1.07x slower                                             |
| logging_silent           | 67.7 ns                                                | 72.6 ns: 1.07x slower                                             |
| async_tree_memoization   | 309 ms                                                 | 334 ms: 1.08x slower                                              |
| scimark_fft              | 198 ms                                                 | 215 ms: 1.09x slower                                              |
| fannkuch                 | 267 ms                                                 | 294 ms: 1.10x slower                                              |
| unpickle_pure_python     | 145 us                                                 | 160 us: 1.11x slower                                              |
| scimark_sor              | 94.1 ms                                                | 106 ms: 1.13x slower                                              |
| nbody                    | 68.6 ms                                                | 79.6 ms: 1.16x slower                                             |
| telco                    | 3.82 ms                                                | 4.74 ms: 1.24x slower                                             |
| hexiom                   | 4.24 ms                                                | 5.29 ms: 1.25x slower                                             |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                      |

Benchmark hidden because not significant (9): tomli_loads, pickle_dict, tornado_http, mako, mypy2, pickle, async_tree_cpu_io_mixed, mdp, pathlib
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, pprint_pformat, pprint_safe_repr, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.24% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
